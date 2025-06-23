---
aliases:
  - bidirectional reflectance distribution function
---

The [[BRDF|bidirectional reflectance distribution function]], is defined as $$f_r(\omega_i,\omega_r)=\frac{\operatorname{d}L_r(\omega_r)}{\operatorname{d}E_i(\omega_i)}=\frac{\operatorname{d}L_r(\omega_r)}{L_i(\omega_i)\cos{\theta_i}\operatorname{d}\omega_i}$$where $L$ is [[radiance]], $E$ is [[irradiance]], and $\theta_i$ is the angle between $\omega_i$ and the surface normal $\vec{n}$. The index $i$ indicates incident light, whereas the index $r$ indicates reflected light.