---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am an Associate Professor (Youth Talent Program) and Master's Supervisor at the School of Mathematical Sciences, Ocean University of China. I received my Ph.D. in Computational Mathematics from the same university in 2022, under the supervision of Prof. Wai Sun Don. 

My research focuses on high-order numerical methods for hyperbolic conservation laws, particularly WENO-type schemes, with emphasis on structure-preserving algorithms (bound-preserving, positivity-preserving, and well-balanced properties) for multi-material flows and surface PDEs. 

<a href='https://scholar.google.com/citations?user=TiPSLVsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

## Research Interests
- High-order numerical methods (WENO, AWENO) for hyperbolic conservation laws
- Hyperbolic conservation laws on manifolds (surface PDEs)
- Physical-constraints-preserving schemes for multi-material flows

## News
- **Aug 2026**: Invited talk at EASIAM 2026, Jeju, South Korea.
- **Jul 2026**: Paper accepted in *Journal of Computational Physics*.
- **Oct 2025**: Invited talk at CSIAM 2025, Changsha, China.
- **Jul 2025**: Received Wiley China Top Download Author Award.
- **Oct 2023**: Shandong Provincial Excellent Doctoral Dissertation.

## Selected Publications
(* denotes corresponding author)

1. Changming Guo, **Bao-Shan Wang**, Wai Sun Don, & Yuanyang Qiao. High-order physical-constraints-preserving velocity-consistent schemes for compressible multicomponent five-equation model with the Mie-Gruneisen equation of state. *Journal of Computational Physics*, 2026, 563, 115049.
   
2. **Bao-Shan Wang**, Alex Shiu Lun Chu, Leevan Ling, & Wai Sun Don. Foliation structures and global flow dynamics of scalar hyperbolic conservation laws on manifolds: I. Geometry-compatible fluxes and numerical validation on sphere and torus. *Communications in Nonlinear Science and Numerical Simulation*, 2026, 152, 109415.

3. **Bao-Shan Wang**, Wai Sun Don, Naveen Kumar Garg, & Alexander Kurganov. Fifth-order A-WENO finite difference schemes based on a new adaptive diffusion central numerical flux. *SIAM Journal on Scientific Computing*, 2020, 42(6), A3932-A3956.

4. **Bao-Shan Wang**, Wai Sun Don, & Peng Li. Fifth-order well-balanced positivity-preserving finite difference AWENO scheme with hydrostatic reconstruction for hyperbolic chemotaxis models. *Applied Numerical Mathematics*, 2023, 186, 41-56.

5. **Bao-Shan Wang**, Peng Li, & Zhen Gao. High order well-balanced and positivity-preserving finite difference AWENO scheme with hydrostatic reconstruction for shallow water equations. *Applied Numerical Mathematics*, 2022, 181, 483-502.

[Full publication list](https://scholar.google.com/citations?user=TiPSLVsAAAAJ)

## Education
- **Ph.D.**, Computational Mathematics, Ocean University of China, 2018–2022 (Supervisor: Prof. Wai Sun Don)
- **M.S.**, Computational Mathematics, Ocean University of China, 2015–2018 (Supervisors: Prof. Zhen Gao & Prof. Wai Sun Don)
- **B.S.**, Mathematics and Applied Mathematics, Ocean University of China, 2011–2015

## Experience
- **Associate Professor (Youth Talent Program)**, Ocean University of China, 2024–present
- **Postdoctoral Researcher**, Ocean University of China, 2022–2024 (Supervisor: Prof. Zhen Gao)
