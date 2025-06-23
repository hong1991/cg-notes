Light incident on a flat surface splits into a reflected part and a reflected part. The amount of light reflected is described by the [[Fresnel reflectance]] $F$.
For a give substance, the Fresnel reflectance canbe defined as $$F(\theta_i)$$, which depends on the incoming angle $\theta_i$.
- When $\theta_i=0\textdegree$, with the light perpendicular to the surface ($l=n$), This value, $F_0$, can be though of as the characteristic [[specular color]] of the substance.
- As $\theta_i$ increase and the light strikes the surface at increasingly glancing angles, the value of $F(\theta_i) will tend to increase,  reaching a value of $1$ at  $\theta_i=90\textdegree$.

An approximation(Schlick): $$F(\vec{n},\vec{l})\approx F_0+(1-F_0)(1-(\vec{n}\cdot\vec{l})^+)^5.$$where $F_0$ can be thought as [[specular color]].