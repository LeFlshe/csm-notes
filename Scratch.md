$$\int _{0}^{\frac{\pi}{2}}e^{2x}\sin(x)dx $$
This looks like integration by parts (although it does smell like it'll be circular)
$$u = \sin(x), dv = e^{2x}$$

| u          | dv                  |
| ---------- | ------------------- |
| $\sin(x)$  | $e^{2x}$            |
| $\cos(x)$  | $\frac{1}{2}e^{2x}$ |
| $-\sin(x)$ | $\frac{1}{4}e^{2x}$ |

Alright hold on, we're going in circles


$$\int_{0}^{\frac{\pi}{2}} \sin(x)e^{2x} = \sin(x) \frac{1}{2}e^{2x} - \cos(x) \frac{1}{4}e^{2x} + \int -\sin(x) \frac{1}{4}e^{2x}$$
Yeah, that's the same thing (with some weird constants floating in front of it)
$$\int \sin(x)e^{2x} = h$$
$$h = \sin(x) \frac{1}{2}e^{2x} - \cos(x) \frac{1}{4}e^ {2x} - \frac{1}{4}h$$
$$\frac{5}{4}h = \sin(x) \frac{1}{2}e^{2x} - \cos(x) \frac{1}{4}e^{2x}$$
$$h = \frac{2}{5}\sin(x)e^{2x} - \frac{1}{5}\cos(x)e^{2x} $$
$$\int\sin(x)e^{2x} = \frac{2}{5}\sin(x)e^{2x} - \frac{1}{5}\cos(x)e^{2x} $$
Gotta do a definite integral, so FTOC time!

$$\int_{0}^{\frac{\pi}{2}} \sin(x)e^{2x}= \left( \frac{2}{5}e^{\pi}\right)- ( -\frac{1}{5})$$
$$\int_{0}^{\frac{\pi}{2}}= \frac{2e^{\pi}+1 }{5}$$

---

$$I = \int 12\cos^{4}(3x)dx$$
$$12\int \cos^2(3x)\cos^2(3x)dx$$
$$u = 3x, du = 3$$
So we got a 1/3 kicking it around
Reduction formula time!
$$\frac{\cos^{3}(u)\sin(u)}{4}+ \frac{3}{4}\int \cos^{2}(u)du$$
That was fun, do it again
$$\frac{\cos^{3}(u)\sin(u)}{4} + \frac{\cos(u)\sin(u)}{2}+ \frac{1}{2}\int 1 du$$
$$\frac{\cos^{3}(u)\sin(u)}{12} + \frac{\cos(u)\sin(u)}{8}+ \frac{u}{8}$$
$$12\left(\frac{\cos^{3}(3x)\sin(3x)}{12} + \frac{\cos(3x)\sin(3x)}{8}+ \frac{3x}{8}\right)$$
$$I = \cos^{3}(3x)\sin(3x) + \frac{3}{2}\cos(3x)\sin(3x) + \frac{9}{2}x+C$$
