#notes #phgn100 #physics

Objective:
To understand how the sum of the torques actuall yapplies to a system.

System is stick + both disks

![[Stick EFBD]]
Saying that counterclockwise is positive, axis of rotation is about the pivot.

Using N2LR
- We kinda just cooked too hard, I'm leaving this here as a monument to our hubris.
$$\vec{W}_{ED_{1}}*d_{1} +\frac{m_{stick}}{L}g\int_{0}^{d_{1}} xdx - \vec{W}_{ED_{2}}*d_{2} -\frac{m_{stick}}{L}g\int_{0}^{d_{2}}xdx =0$$

---


$$m_{1}*d_{1} -m_{2}*d_{2} - m_{stick}(\frac{L}{2}-d_{1})=0$$
$$m_{1}*d_{1}-m_{stick}(\frac{L}{2}-d_{1})=m_{2}d_{2}$$
$$d_{2}= \frac{d_1m_{1}- m_{stick}(\frac{L}{2}-d_{1})}{m_2}$$


Determining where they should be placed

| Pivot | Theoretical | Experiment | Percent Difference |
| ----- | ----------- | ---------- | ------------------ |
| 10    | 6 (16)            | 6 (16)           | 0%                   |
| 13    | 10.5 (23.5)            | 10.5 (23.5)           | 0%                   |
| 16      | 15 (31)            | 15 (31)           | 0%                   |

Values in () are the actual placement upon the meter stick
All of our values were exactly accurate.

## Follow Up Questions
1. Learned how the sum of the torques actually applies, and in situations where the pivot is not at the center of mass, you need to check the rotating object itself.
2. Still a smidge confused as to why we don't need to do an integral or some other in order to consider all the minute torques of the different parts of the beam acting, but working through the math did make me realize that you need to be certain that you're actually solving the correct equations and not just ending up with the length of stick or some other shenanigans. 