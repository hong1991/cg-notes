Parameters:

| name                         | description                                                                                                                                                                                                        |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| baseColor                    | the surface color, usually supplied by texture maps                                                                                                                                                                |
| subsurface                   | controls diffuse shape using a subsurface approximation.                                                                                                                                                           |
| metallic                     | the metallic-ness(0 = dielectric, 1= metallic). This is a linear blend between two different models. The metallic model has no diffuse component and also has a tinted incident specular, equal to the base color. |
| [[specular color\|specular]] | incident specular amount. This is in lieu of an explicit index-of-refraction.                                                                                                                                      |

Diffuse model:$$f_d=\frac{baseColor}{\pi}(1+(F_{D90}-1)(1-\cos \theta_l)^5)(1+(F_{D90}-1)(1-\cos \theta_v)^5)$$where $$F_{D90}=0.5+2\cdot roughness \cdot \theta_d.$$
A novel empirical model for diffuse retroreflection