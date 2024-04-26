 #phgn100 #physics

Functions:
Object 1 position = $\vec r_{1}(t)=At^{2}\hat\imath+B\hat\jmath$
Object 2 pos = $\vec r_{2}(t)=Ce^{-Dt}\hat\imath$
ABCD are all positive, unknown constants.

Mass of object 1 is $m_{1}$ and mass of object 2 is $m_{2}$

Part a)
![[PSSD A 1 17]]


---
Part b)
$$
\vec r_{cm}=\frac{m_{1}(A t^{2}+\hat\imath+B\hat\jmath)+m_{2}(Ce^{-Dt}\hat\imath)}{m_{1}+m_{2}}
$$
$$\vec r_{cm}= \frac{m_{1}At^{2}\hat\imath+m_{1}B\hat\jmath+m_{2}Ce^{-Dt}\hat\imath}{m_{1}+m_{2}}$$
$$r_{cm,x}= (m_{1}At^{2}+m_{2}Ce^{-Dt})$$
$$r_{cm,y}=m_{1}B$$
$$\vec r_{cm}= \frac{r_{cm,x} \ + r_{cm,y}}{m_{1}+m_{2}}$$


---
Part c)
Quotient rule written out so I don't feel like a fool
$$\frac{d}{dt}= \frac{L dH - HdL}{L^{2}}$$
$m_{1}+m_{2}$ is just going to be a constant, so the derivative of the denominator in quotient rule is just 0
$$\vec v= \frac{(m_{1}+m_{2})(r_{cm,x} + r_{cm,y})}{(m_{1}+m_{2})^{2}}$$
$$\vec v = \frac{\frac{d}{dt}(r_{cm,x}+r_{cm,y})}{m_{1}+m_{2}}$$
$$\vec v = \frac{(2t m_{1}A  -m_{2}CDe^{-Dt})\hat\imath   + B\hat\jmath}{m_{1}+ m_{2}}$$

---
Part d)
$$\vec v_{cm}(t) = \frac{m_{1}\vec v_{1}(t) + m_{2}\vec v_{2}(t)}{m_{1}+m_{2}}$$
Very similar to the position, but instead a weighted average of the velocities

$$\vec v_{cm} = \frac{1}{m_{tot}} \sum\limits_{j} m_{j}\vec v_j$$

---

Follow up questions: 
1. The biggest concept I learned / solidified was how center of mass is just a weighted average of the positions of various objects, and how intrinsically the velocity of center of mass is to position - you just need to consider the velocity of all the objects, instead of just where it is.
2. The most confusing part of this PSSD was attempting to simplify the equation and take the derivative, until we realized that all the variables (aside from $t$) really just represent constants - which made the derivative much easier to take, especially when considering that the derivative of a constant is 0. 