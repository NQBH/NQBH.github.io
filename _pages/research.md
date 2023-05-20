---
permalink: /research/
title: "Research"
text-align: justify
toc: true
---
{% include toc %}

------

Advanced Mathematics
======
------
### Inverse Problems (IPs)

* Exposition.

------

### Porous Medium Equations (PMEs)
PMEs: $\partial_tu - \Delta u^m + u^{-\beta}\chi_{\{ u>0 \}} = 0$ in $(0,\infty)\times\mathbb{R}^N$.

* Nguyen Quan Ba Hong's. *Multidimensional Degenerate Diffusion Equation with a Very Strong Absorption & A Source Term*. [[pdf](https://github.com/NQBH/miscellaneous/blob/master/bachelor_of_science/bachelor_thesis/NQBH_bachelor_thesis.pdf)]. [[slide](https://github.com/NQBH/miscellaneous/blob/master/bachelor_of_science/bachelor_thesis/NQBH_bachelor_thesis_slide.pdf)]. HCMUS. Jul 2018.

* Nguyen Anh Dao, Jesus Ildefonso Diáz, Quan Ba Hong Nguyen. *Pointwise Gradient Estimates in Multi-dimensional Slow Diffusion Equations with a Singular Quenching Term*. Advanced Nonlinear Studies. [[link](https://www.degruyter.com/document/doi/10.1515/ans-2020-2076/html)]. [[pdf](https://github.com/NQBH/reference/blob/master/Dao_Diaz_Nguyen2020.pdf)]. doi: [`10.1515/ans-2020-2076`](https://doi.org/10.1515/ans-2020-2076).

------

### Finite Volume Methods (FVMs)

* Nguyen Quan Ba Hong's Master Thesis. *Staggered & Well-Balanced Discretization of Shallow Water Equations*. [[pdf](https://github.com/NQBH/miscellaneous/blob/master/master_of_science/master_thesis/NQBH_master_thesis.pdf)]. [[slide](https://github.com/NQBH/miscellaneous/blob/master/master_of_science/master_thesis/NQBH_master_thesis_slide.pdf)]. UR1. Jun 2019.

------

### Turbulence Models
Navier--Stokes equations, $k$-$\varepsilon$ turbulence model(s) (several variants), $k$-$\omega$ turbulence model.

$$\nabla\cdot(\rho{\bf u}) = 0$$,
$$\partial_t(\rho{\bf u}) + \nabla\cdot(\rho{\bf u}\otimes{\bf u}) = \nabla\cdot[(\mu + \mu_{\rm t})\nabla{\bf u}] + {\bf Q}^{\bf u}$$,
$$\partial_t(\rho k) + \nabla\cdot(\rho{\bf u}k) = \nabla\cdot\left(\left(\mu + \frac{\mu_{\rm t}}{\sigma_k}\right)\nabla k\right) + P_k - \rho\varepsilon$$,
$$\partial_t(\rho\varepsilon) + \nabla\cdot(\rho{\bf u}\varepsilon) = \nabla\cdot\left(\left(\mu + \frac{\mu_{\rm t}}{\sigma_\varepsilon}\right)\nabla\varepsilon\right) + C_{\varepsilon1}\frac{\varepsilon}{k}P_k - C_{\varepsilon2}\rho\frac{\varepsilon^2}{k}$$.

------