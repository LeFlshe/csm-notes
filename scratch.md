$$\iint_{D}\sqrt{y^{2}-x^{2}}dA$$
$$y-x=0, y-x=2, y+x=0, y+x=2$$
$$u=y+x, v=y-x$$
$$\iint_{D}\sqrt{uv}\ |J(u,v)| dA$$
$$\int_{0}^{2} \int_{0}^{2}\sqrt{uv} * J(u,v)dudv$$
$$y= u-x $$
$$x= y-v $$
$$y = u - y + v, y = \frac{u+v}{2}$$
$$x= u -x -v$$
$$x = \frac{u-v}{2}$$
$$J(u,v) = \det \Big| \begin{matrix} \frac{1}{2} & -\frac{1}{2} \\ \frac{1}{2} & \frac{1}{2}\end{matrix}\Big|= \frac{1}{2}$$
$$\frac{1}{2}\int_{0}^{2}\int_{0}^{2}\sqrt{uv}  \ dudv= \frac{1}{2} \int_{0}^{2} \left(\frac{2\sqrt{v}u^{\frac{3}{2}}}{3}\Big|_{0}^{2}\right )$$
$$ \frac{1}{2}\cdot\frac{2}{3}2^{\frac{3}{2}} \left(\frac{2}{3}  v^{\frac{3}{2} } \Big|_{0}^{2} \right) = \frac{4}{18}*8 = \frac{32}{18}= \frac{16}{9}$$

