$$z=\sqrt{\frac{x^{2}+y^{2}}{3}}$$
$$x^{2}+y^{2}+z^{2}= 12$$
$$z= \sqrt{12-x^{2}-y^{2}}$$
$$\int_\sqrt{12}^{\sqrt{12}} \int_{-\sqrt{12-x^{2}}}^{\sqrt{12-x^{2}}} \left( \int _{\sqrt{12-x^{2-y^{2}}}} ^{\sqrt{\frac{x^{2}+y^{2}}{3}}}1\right)dzdydx$$
----

$$x^{2}+ y^{2}=r^{2}, z= \sqrt{\frac{r^{2}}{3}}, z = \sqrt{12-r^{2}}$$
$$\sqrt{\frac{r^{2}}{3}}= \sqrt{12-r^{2}}$$
$$\frac{r^{2}}{3}= 12-r^{2}, 4r^{2}=36, r= 3$$
$$ \int_{0}^{2\pi} \int_{0}^{3}\int_{\sqrt{12-r^{2}}}^{\sqrt{\frac{r^{2}}{3}}}r \ dr\ d\theta$$

----

$$\rho^{2}= 12, \rho = \sqrt{12} (2\sqrt{3}, \text{but I prefer }\sqrt{12})$$
$$\rho\cos\phi = \sqrt{\frac{(\rho\sin\phi)^{2}}{3}}, \rho^{2}\cos^{2}\phi = \rho^{2}\sin^{2}\phi *\frac{1}{3}$$
$$\cos^{2} \phi = \frac{1}{3}\sin^{2}\phi$$
$$1- \sin^{2}\phi = \frac{1}{3}\sin^{2}\phi, 1 = \frac{4}{3}\sin^{2}\phi$$
$$\sin^{2}\phi = \frac{3}{4}, \phi = \sin^{-1}\left( \sqrt{\frac{3}{4}}\right)$$
$$0 \leq \rho \leq \sqrt{12}$$
$$0 \leq \phi \leq \frac{\pi}{3}$$
$$0 \leq \theta \leq 2\pi$$
$$\int_{0}^{2\pi}\int_{0}^{\frac{\pi}{3}}\int_{0}^{\sqrt{12}}1 \rho^{2}\sin\phi  \ d\rho \ d\phi \ d\theta$$
----


$$\int_{0}^{2\pi}\int_{0}^{\frac{\pi}{3}} \left(\frac{\rho^{3}}{3}\sin\phi \Big|_{0}^{\sqrt{12}}\right)d\phi d\theta$$
$$\int_{0}^{2\pi} \int_{0}^{\frac{\pi}{3}} \frac{144}{3}\sin\phi \ d\phi d\theta$$
$$\frac{144}{3}\int_{0}^{2\pi}\left(-\cos\phi\Big|_{0}^{\frac{\pi}{3}}\right) d\theta$$
$$\frac{144}{3}\int_{0}^{2\pi }( -\frac{1}{2}- 1)d\theta$$
$$\frac{144}{3}* - \frac{3}{2}( \theta\Big|_{0}^{2\pi})$$
$$\frac{144}{3}* - \frac{3}{2}* 2\pi= 144\pi$$
