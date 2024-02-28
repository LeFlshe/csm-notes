#notes #phgn100 #physics

System is the satellite
Using right is the positive x direction ($\hat\imath$), up is the positive y direction $(\hat\jmath)$, and into the page is the positive z direction $(\hat k)$ 


![[Satellite Sketch]]
We've got a satellite going counterclockwise

b. $$\vec{r} \times \vec{f}_{G,ES}= <0,0,0>$$

$$<r,0, 0>$$
$$<F,0,0>$$
$$0 - 0 +0 = <0, 0, 0>$$
Cross product of the two colinear vectors just goes to 0

c. 

So the velocity vector $\vec{v}_{s}=v_{o}<0,-1,0>$ (as we've currently drawn the picture)

So the cross product $\vec{v}_{s}\times\vec{r}$ 

$$<0, -v_{o}, 0>$$
$$<r,0,0>$$
So the cross product = $<0, 0, -(-v_{o}*r)>$= $<0,0,v_{o}r>$ 
So the magnitude is just $v_{o}r$, and the direction is going to be into the page, or positive $\hat k$ 


d. 

$\frac{d}{dt}<0,0,v_{o}r> = <0,0,0>$


$$<0,0,0> = \frac{1}{m_{s}} <0,0,0>$$
$$<0,0,0> = <0,0,0>$$
This is absolutely true for a circular orbit! $v_{o}r$ is a constant, so when you take its derivative, you end up with 0, and $\vec{r}\times\vec{F}_{net}$ is $<0,0,0>$, and any scalar on a 0 vector is in fact still.... $<0,0,0>$


e. 

![[Elliptical Orbit Sketch]]


$$\frac{d}{dt}( <r_{2},0,0>\times <0,v_{2},0> )\ = \frac{1}{m_{s}} ( r_{2}\times F_{net}) = \frac{d}{dt}(<r_{1},0,0>\times<0,v_{1},0>)$$




$$\int \frac{d}{dt}(<r_{2},0,0> \times <0,v_{2},0>) = \int \frac{d}{dt}(<r_{1},0,0> \times <0,v_{1},0>)$$
$$<r_{2},0,0> \times <0,-v_{2},0> = <r_{1},0, 0> \times <0, v_{1}, 0>$$

$$<0,0,-v_{2}r_{2}> \ = <0,0, v_{1}r_{1}>$$
$$=-v_{2}r_{2}<0,0,1> = v_{1}r_{1}<0,0,1>$$
$$-v_{2}r_{2}= v_{1}r_{1}$$
$$v_{2}= \frac{v_{1}r_{1}}{-r_{2}}$$


---

1. I learned some mathematical tricks - if things are equal to one thing, you can kill the middleman, and suddenly, you have an equation you can actually solve. 
2. I had initially found solving the equation in part $f$ very difficult, but realizing that you could use the integral as an operator to kill the $\frac{d}{dt}$ derivative operator, and setting things equal to $<0,0,0>$ lets algebra actually happen. 