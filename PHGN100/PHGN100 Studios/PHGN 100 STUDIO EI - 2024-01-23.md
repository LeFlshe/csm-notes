 #phgn100 #physics

- Alrighty, goal is to make it so a ball bearing hits Blaster (center of mass at $y_{f}$), and what $x_{f}$ needs to be set to in order to make that a reality

- Sketch

![[Shooting Blaster Sketch]]

---

- We have accelerations ($a_{x}$=0, $a_{y}=g$)
	- So $v_{x}(t)=v_{i}*\cos\theta$
	- and $v_{y}(t)=v_{i}*\sin\theta-gt$
		- Continuing to integrate in order to get position
			- $x(t)=v_{i}*\cos(\theta)*t$
			- $y(t)=y_{i}+v_{i}\sin(\theta)t- \frac{1}{2}gt^{2}$
				- making sure not to get forget initial height
- In order to get time to hit Blaster, 
	- $y_{f}=y_{i}+ v_{i}\sin(\theta)t - \frac{1}{2}gt^{2}$
	- $1.33m =1.26m +4.536\text{m/s}*\sin(30)t - \frac{1}{2}9.81\text{m/s}^2*t^{2}$
		- $1.33=1.26 +2.268t- 4.905t^{2}$
		- $-4.905t^{2}+2.268t-0.07=0$
		- And now solving this for $t$
			- $\frac{-2.268\pm\sqrt{2.268^{2}-4(-4.905)(-0.07)}}{2(-4.905)}$
			- Which has a positive 0 at 0.43
				- Or at 0.03s
				- 0.429s
					- Let's go with 0.43
- So then the x pos would just be $x(t)=4.536*\cos(30)*0.43= 1.689$m
	- Alternative position of 0.12 m


Questions
1. This definitely reinforced that it's only vertical velocity that changes in simple projectile motion - it's one thing to read and do math that it doesn't change, and another thing to fire a projectile and smack a poor, innocent Blaster with the results of your labor.
2. I'm a tad confused about why we hit blaster in the head instead of center of mass - my group discussed and we believe it to be from random variance in the actual initial velocity, or the launcher could be not at perfectly $30\degree$, either of which would cause the projectile to travel a slightly larger/shorter distance, leading to impacting Blaster in the head. 