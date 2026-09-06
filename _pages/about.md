---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.home-hero {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 2rem;
  margin: 1rem 0 2rem 0;
  padding: 1rem 0;
}
.home-hero__text {
  flex: 1.2;
}
.home-hero__eyebrow {
  font-size: 0.85rem;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  color: #6c757d;
  margin-bottom: 0.25rem;
}
.home-hero__text h1 {
  font-size: 2.8rem;
  margin: 0.25rem 0 0.5rem 0;
  font-weight: 400;
}
.home-hero__lead {
  font-size: 1.2rem;
  color: #3c3c3c;
  margin-bottom: 0.75rem;
}
.home-hero__actions {
  margin-top: 1rem;
}
.home-button {
  display: inline-block;
  padding: 0.5rem 1.2rem;
  border: 1px solid #d1d1d1;
  border-radius: 4px;
  font-size: 0.9rem;
  color: #333;
  text-decoration: none;
  margin-right: 0.5rem;
  transition: all 0.2s;
}
.home-button:hover {
  background-color: #f0f0f0;
  border-color: #aaa;
  text-decoration: none;
}
.home-button--primary {
  background-color: #2a7ae2;
  border-color: #2a7ae2;
  color: white;
}
.home-button--primary:hover {
  background-color: #1a5bbf;
  border-color: #1a5bbf;
  color: white;
}
.home-hero__image {
  flex: 0.8;
  text-align: center;
}
.home-hero__image img {
  max-width: 100%;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
}
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.5rem;
  margin: 1rem 0;
}
.research-grid article {
  background: #f8f9fa;
  padding: 1.2rem 1.5rem;
  border-radius: 6px;
}
.research-grid h3 {
  margin-top: 0;
  font-size: 1.1rem;
}
.academic-timeline {
  margin: 1rem 0;
}
.academic-timeline__item {
  display: flex;
  gap: 1.5rem;
  padding: 0.8rem 0;
  border-bottom: 1px solid #eee;
}
.academic-timeline__date {
  flex: 0 0 180px;
  font-weight: 600;
  color: #2a7ae2;
}
.academic-timeline__content {
  flex: 1;
}
.academic-timeline__content h3 {
  margin: 0 0 0.1rem 0;
  font-size: 1.05rem;
}
.academic-timeline__institution {
  margin: 0.1rem 0 0.3rem 0;
  color: #555;
  font-style: italic;
}
.academic-timeline__institution span {
  color: #888;
}
.visiting-list {
  margin: 1rem 0;
}
.visiting-list__item {
  display: flex;
  gap: 1.5rem;
  padding: 0.8rem 0;
  border-bottom: 1px solid #eee;
}
.visiting-list__date {
  flex: 0 0 180px;
  font-weight: 600;
  color: #2a7ae2;
}
.anchor {
  display: block;
  position: relative;
  top: -70px;
  visibility: hidden;
}
@media (max-width: 768px) {
  .home-hero { flex-direction: column; }
  .academic-timeline__item { flex-direction: column; gap: 0.2rem; }
  .visiting-list__item { flex-direction: column; gap: 0.2rem; }
  .academic-timeline__date { flex: 1; }
  .visiting-list__date { flex: 1; }
}
</style>

<!-- ===== HERO SECTION ===== -->
<section class="home-hero">
  <div class="home-hero__text">
    <p class="home-hero__eyebrow">High-Order Numerical Methods | Hyperbolic Conservation Laws | WENO Schemes</p>
    <h1>Bao-Shan Wang</h1>
    <p class="home-hero__lead">Associate Professor at Ocean University of China.</p>
    <p>
      My research focuses on high-order numerical methods for hyperbolic conservation laws, particularly WENO-type schemes, with emphasis on structure-preserving algorithms (bound-preserving, positivity-preserving, and well-balanced properties) for multi-material flows and surface PDEs.
    </p>
    <p class="home-hero__actions">
      <a class="home-button home-button--primary" href="#publications">Publications</a>
      <a class="home-button" href="https://scholar.google.com/citations?user=TiPSLVsAAAAJ">Google Scholar</a>
      <a class="home-button" href="https://www.researchgate.net/profile/Baoshan-Wang">ResearchGate</a>
    </p>
  </div>
  <div class="home-hero__image">
    <img src="/images/profile.jpg" alt="Bao-Shan Wang" onerror="this.style.display='none'">
  </div>
</section>

<!-- ===== ABOUT ===== -->
<span class="anchor" id="about-me"></span>
<h1 id="about-me">About Me</h1>

<p>I am an Associate Professor and Master's Supervisor at the School of Mathematical Sciences, Ocean University of China. I received my Ph.D. in Computational Mathematics from the same university in 2022, under the supervision of Prof. Wai Sun Don.</p>

<p>My research spans high-order finite difference and finite volume WENO schemes, affine-invariant WENO operators, physical-constraints-preserving schemes for multi-material flows, and hyperbolic conservation laws on manifolds via the time-continuous embedding method.</p>

<!-- ===== RESEARCH HIGHLIGHTS ===== -->
<span class="anchor" id="research"></span>
<h1 id="research-highlights">Research Highlights</h1>

<div class="research-grid">
  <article>
    <h3>High-Order WENO Schemes</h3>
    <p>Design and analysis of high-order WENO, AWENO, and hybrid schemes for hyperbolic conservation laws, including affine-invariant weights and adaptive diffusion fluxes.</p>
  </article>
  <article>
    <h3>Physical-Constraints-Preserving Methods</h3>
    <p>Bound-preserving, positivity-preserving, and well-balanced schemes for multi-material flows, Euler equations under gravitational fields, and shallow water models.</p>
  </article>
  <article>
    <h3>Surface PDEs &amp; Manifolds</h3>
    <p>Time-continuous embedding method and foliation structures for hyperbolic conservation laws on curved surfaces and manifolds.</p>
  </article>
</div>

<!-- ===== APPOINTMENTS ===== -->
<span class="anchor" id="appointments"></span>
<h1 id="appointments">Appointments</h1>

<div class="academic-timeline">
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">Sep 2024 – Present</div>
    <div class="academic-timeline__content">
      <h3>Associate Professor (Youth Talent Program), Master's Supervisor</h3>
      <p class="academic-timeline__institution">School of Mathematical Sciences, Ocean University of China <span>Qingdao, China</span></p>
    </div>
  </article>
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">Aug 2022 – Sep 2024</div>
    <div class="academic-timeline__content">
      <h3>Postdoctoral Researcher</h3>
      <p class="academic-timeline__institution">School of Mathematical Sciences, Ocean University of China <span>Qingdao, China</span></p>
      <p>Supervisor: Prof. Zhen Gao.</p>
      <p>Research on high-order physical-constraints-preserving AWENO schemes for multi-material flows.</p>
    </div>
  </article>
</div>

<!-- ===== EDUCATION ===== -->
<span class="anchor" id="education"></span>
<h1 id="education">Education</h1>

<div class="academic-timeline">
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">Sep 2018 – Jun 2022</div>
    <div class="academic-timeline__content">
      <h3>Ph.D. in Computational Mathematics</h3>
      <p class="academic-timeline__institution">Ocean University of China <span>Qingdao, China</span></p>
      <p>Supervisor: Prof. Wai Sun Don.</p>
      <p>Thesis: <em>Physical-Constraints-Preserving High-Order WENO Schemes</em>.</p>
    </div>
  </article>
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">Sep 2015 – Jun 2018</div>
    <div class="academic-timeline__content">
      <h3>M.Sc. in Computational Mathematics</h3>
      <p class="academic-timeline__institution">Ocean University of China <span>Qingdao, China</span></p>
      <p>Supervisors: Prof. Zhen Gao &amp; Prof. Wai Sun Don.</p>
      <p>Thesis: <em>Radial Basis Function Based Shock Detection Algorithm and Its Application in High-Order Hybrid Schemes</em>.</p>
    </div>
  </article>
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">Aug 2011 – Jun 2015</div>
    <div class="academic-timeline__content">
      <h3>B.Sc. in Mathematics and Applied Mathematics</h3>
      <p class="academic-timeline__institution">Ocean University of China <span>Qingdao, China</span></p>
    </div>
  </article>
</div>

<!-- ===== VISITING EXPERIENCE ===== -->
<span class="anchor" id="visiting"></span>
<h1 id="visiting-experience">Visiting Experience</h1>

<div class="visiting-list">
  <article class="visiting-list__item">
    <p class="visiting-list__date">Jan 2026 / Sep 2026</p>
    <div>
      <h3>Visiting Scholar</h3>
      <p><strong>Hong Kong Baptist University</strong> | Department of Mathematics</p>
      <p>Hosts: Prof. Leevan Ling (Department Head) &amp; Prof. Wai Sun Don.</p>
    </div>
  </article>
  <article class="visiting-list__item">
    <p class="visiting-list__date">Dec 2025 – Jan 2026</p>
    <div>
      <h3>Visiting Professor</h3>
      <p><strong>Pohang University of Science and Technology (POSTECH)</strong> | Department of Mathematics</p>
      <p>Hosts: Prof. Jae-Hun Jung (Dean of Natural Sciences) &amp; Dr. Jiaxi Gu.</p>
    </div>
  </article>
  <article class="visiting-list__item">
    <p class="visiting-list__date">Nov 2023 – May 2024</p>
    <div>
      <h3>Visiting Scholar</h3>
      <p><strong>Southern University of Science and Technology (SUSTech)</strong> | Shenzhen, China</p>
      <p>Host: Prof. Alexander Kurganov (Chair Professor).</p>
    </div>
  </article>
</div>

<!-- ===== CONFERENCE ORGANIZATION ===== -->
<span class="anchor" id="conference-organization"></span>
<h1 id="conference-organization">Conference Organization</h1>

<ul>
  <li><strong>Mini-Symposium Co-Organizer:</strong> <a href="#">EASIAM 2026</a>, "High-Order Numerical Methods for Hyperbolic Conservation Laws," Jeju, South Korea, Aug 2026.</li>
  <li><strong>Mini-Symposium Co-Organizer:</strong> <a href="#">ICOSAHOM 2023</a>, "Recent Developments in Physical-Property-Preserving WENO Schemes and DG Methods for Hyperbolic Single- and Multi-Medium Models," Yonsei University, Seoul, South Korea, Aug 2023.</li>
</ul>

<!-- ===== SELECTED PRESENTATIONS ===== -->
<span class="anchor" id="presentations"></span>
<h1 id="selected-presentations">Selected Presentations</h1>

<ul>
  <li><strong>Invited Talk:</strong> "Foliation Structures and Global Flow Dynamics of Scalar Hyperbolic Conservation Laws on Manifolds," <a href="#">EASIAM 2026</a>, Jeju, South Korea, Aug 2026.</li>
  <li><strong>Invited Talk:</strong> "High-Order Physical-Constraints-Preserving Velocity-Consistent Schemes for Compressible Multicomponent Five-Equation Model with the Mie-Gruneisen Equation of State," Kunming University of Science and Technology, Aug 2026.</li>
  <li><strong>Invited Talk:</strong> "A Family of Bound-Preserving Velocity-Consistent Schemes for Two-Medium γ-Based Model with Stiffened Gas," <a href="#">CSIAM 2025 Annual Meeting</a>, Changsha, China, Oct 2025.</li>
  <li><strong>Invited Talk:</strong> "Time-Continuous Embedding Method for Hyperbolic Conservation Laws on Manifolds," Hong Kong Baptist University, Nov 2024.</li>
  <li><strong>Invited Talk:</strong> "Affine-Invariant WENO Operator and Applications in Solving Hyperbolic Conservation Laws," <a href="#">Workshop on Development of High-Order Methods for Hyperbolic PDEs</a>, SUSTech, Shenzhen, Mar 2024.</li>
</ul>

<!-- ===== AWARDS AND SERVICE ===== -->
<span class="anchor" id="awards-service"></span>
<h1 id="awards-and-service">Awards and Service</h1>

<ul>
  <li><strong>Shandong Provincial Excellent Doctoral Dissertation</strong> (2023).</li>
  <li><strong>National Scholarship for Doctoral Students</strong> (2021).</li>
  <li><strong>Outstanding Graduate Student of the Year</strong>, Ocean University of China (Top 10, 2021).</li>
  <li><strong>Shandong Provincial Excellent Master's Thesis</strong> (2019).</li>
  <li><strong>National Scholarship for Master's Students</strong> (2017).</li>
  <li><strong>National First Prize</strong>, Postgraduate Mathematical Contest in Modeling (2016).</li>
  <li><strong>Journal Referee</strong> for <em>Journal of Computational Physics</em> (29), <em>Applied Numerical Mathematics</em> (26), <em>Advances in Applied Mathematics and Mechanics</em> (10), <em>Communications in Nonlinear Science and Numerical Simulation</em> (6), <em>Computers &amp; Fluids</em> (6), and 19 other journals.</li>
</ul>

<!-- ===== RESEARCH GRANTS ===== -->
<span class="anchor" id="grants"></span>
<h1 id="research-grants">Research Grants</h1>

<div class="academic-timeline">
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">2024–2026</div>
    <div class="academic-timeline__content">
      <h3>NSFC Youth Program (PI, RMB 300,000)</h3>
      <p class="academic-timeline__institution">Time-Continuous Closest Point Method for Hyperbolic Conservation Laws on Manifolds</p>
    </div>
  </article>
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">2025–2027</div>
    <div class="academic-timeline__content">
      <h3>OUC Youth Talent Program Start-up Fund (PI, RMB 300,000)</h3>
      <p class="academic-timeline__institution">High-Order Physical-Constraints-Preserving Numerical Methods for Multi-Material Flow Models under Extreme Conditions</p>
    </div>
  </article>
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">2026–2028</div>
    <div class="academic-timeline__content">
      <h3>Shandong Higher Education Youth Innovation Team (PI)</h3>
      <p class="academic-timeline__institution">Physical-Constraints-Preserving Numerical Methods for Multi-Material Flow Models</p>
    </div>
  </article>
</div>

<!-- ===== TECHNICAL SKILLS ===== -->
<span class="anchor" id="skills"></span>
<h1 id="technical-skills">Technical Skills</h1>

<ul>
  <li><strong>Programming:</strong> MATLAB, Fortran, LaTeX, Linux shell scripting.</li>
  <li><strong>Research Interests:</strong> High-order WENO/AWENO schemes, affine-invariant operators, physical-constraints-preserving methods, surface PDEs, multi-material flows.</li>
  <li><strong>Other:</strong> Founder of WeChat public account "Taylor's Formula" (台劳公式, 3,100+ followers).</li>
</ul>

<!-- ===== PUBLICATIONS ===== -->
<span class="anchor" id="publications"></span>
<h1 id="publications">Publications</h1>

<p>(* denotes corresponding author; # denotes equal contribution; IF = Impact Factor; Total Citations = 484; H-Index = 13)</p>

<h2 id="journal-articles">Journal Articles</h2>

<ol>
  <li>Changming Guo, <strong>Bao-Shan Wang</strong>#, Wai Sun Don#, &amp; Yuanyang Qiao#. <a href="https://doi.org/10.1016/j.jcp.2026.115049">High-order physical-constraints-preserving velocity-consistent schemes for compressible multicomponent five-equation model with the Mie-Gruneisen equation of state</a>. <em>Journal of Computational Physics</em>, 2026, 563, 115049. (IF: 3.8)</li>

  <li>Ya-Ru Zhao, Zhen Gao, &amp; <strong>Bao-Shan Wang</strong>*. <a href="https://doi.org/10.1016/j.jcp.2025.114409">Fifth-order equilibrium-preserving path-conservative characteristic-wise AWENO scheme for one-fluid two-temperature Euler model</a>. <em>Journal of Computational Physics</em>, 2026, 544, 114409. (IF: 3.8)</li>

  <li>Xiao-Shuo Xiang, Peng Li, Zhen Gao, &amp; <strong>Bao-Shan Wang</strong>*. <a href="https://doi.org/10.1016/j.apnum.2026.02.001">High-order well-balanced positivity-preserving affine-invariant finite volume CWENOZ scheme with LDCU flux for the Euler equations under gravitational fields</a>. <em>Applied Numerical Mathematics</em>, 2026, 224, 181–206. (IF: 2.4)</li>

  <li><strong>Bao-Shan Wang</strong>, Alex Shiu Lun Chu, Leevan Ling, &amp; Wai Sun Don*. <a href="https://doi.org/10.1016/j.cnsns.2025.109415">Foliation structures and global flow dynamics of scalar hyperbolic conservation laws on manifolds: I. Geometry-compatible fluxes and numerical validation on sphere and torus</a>. <em>Communications in Nonlinear Science and Numerical Simulation</em>, 2026, 152, 109415. (IF: 3.8)</li>

  <li>Xiao-Shuo Xiang, Peng Li, &amp; <strong>Bao-Shan Wang</strong>*. <a href="https://doi.org/10.1016/j.aml.2026.110046">Finite-volume WENO scheme on non-uniform mesh for 3D detonation simulation</a>. <em>Applied Mathematics Letters</em>, 2026, 182, 110046. (IF: 2.7)</li>

  <li>Kang-Bo Tian, <strong>Bao-Shan Wang</strong>, Xiao Wen, &amp; Zhen Gao*. <a href="https://doi.org/10.4208/eajam.2025-063">High order well-balanced and positivity-preserving AWENO scheme for rotating shallow water equations with Coriolis force</a>. <em>East Asian Journal on Applied Mathematics</em>, 2026, 16(4), 714–741. (IF: 1.1)</li>

  <li>Wai Sun Don#, Jia-Le Li#, Leevan Ling#, <strong>Bao-Shan Wang</strong>#, &amp; Yinghua Wang#. <a href="https://doi.org/10.1007/978-3-031-76988-7_12">Hybrid high-order shock-capturing scheme for one-dimensional hyperbolic conservation laws on manifolds (surface PDEs) in the time-continuous embedding framework</a>. In: S. Chun, J.-H. Jung, E.J. Park, J. Shen (eds), <em>Spectral and High-Order Methods for Partial Differential Equations ICOSAHOM 2023. Lecture Notes in Computational Science and Engineering</em>, vol. 142, Springer, Cham, 2025, pp. 239–255.</li>

  <li><strong>Bao-Shan Wang</strong> &amp; Wai Sun Don*. <a href="https://doi.org/10.1007/978-981-96-4767-5_6">Fifth-order bound-, positivity-, and equilibrium-preserving affine-invariant AWENO scheme for two-medium γ-based model of stiffened gas</a>. In: R.S. Myong and H.D. Kim (eds), <em>Proceedings of the 34th International Symposium on Shock Waves, Volume 1: Fundamentals</em>, Springer, Singapore, 2025, pp. 59–71.</li>

  <li>Qingcheng Fu, Yaguang Gu*, Alexander Kurganov, &amp; <strong>Bao-Shan Wang</strong>. <a href="https://doi.org/10.1007/s10915-025-03003-y">Bound- and positivity-preserving path-conservative central-upwind AWENO scheme for the five-equation model of compressible two-component flows</a>. <em>Journal of Scientific Computing</em>, 2025, 104(3), 94. (IF: 3.3)</li>

  <li>Changming Guo, Yuanyang Qiao, Wai Sun Don, &amp; <strong>Bao-Shan Wang</strong>*. <a href="https://doi.org/10.1016/j.jcp.2025.114149">A family of bound-preserving velocity-consistent schemes for two-medium γ-based model with stiffened gas</a>. <em>Journal of Computational Physics</em>, 2025, 538, 114149. (IF: 3.8)</li>

  <li>Cai-Feng Wang#, Wai Sun Don#, Jia-Le Li#, &amp; <strong>Bao-Shan Wang</strong>#. <a href="https://doi.org/10.4208/aamm.OA-2024-0037">Improved sixth-order WENO finite difference schemes for hyperbolic conservation laws</a>. <em>Advances in Applied Mathematics and Mechanics</em>, 2025, 17(6), 1591–1624. (IF: 1.1)</li>

  <li>Jia-Le Li, Wai Sun Don, Cai-Feng Wang, &amp; <strong>Bao-Shan Wang</strong>*. <a href="https://doi.org/10.4208/aamm.OA-2023-0306">Spatial-temporal adaptive-order positivity-preserving WENO finite difference scheme with relaxed CFL condition for Euler equations with extreme conditions</a>. <em>Advances in Applied Mathematics and Mechanics</em>, 2025, 17(3), 804–839. (IF: 1.5)</li>

  <li>Zhen Gao, Zi-Yu Tang, <strong>Bao-Shan Wang</strong>*, &amp; Ya-Ru Zhao. <a href="https://doi.org/10.1002/num.23170">Novel high-order alternative finite difference central WENO schemes for hyperbolic conservation laws</a>. <em>Numerical Methods for Partial Differential Equations</em>, 2025, 41(2), e23170. (IF: 2.1)</li>

  <li>Xiao-Shuo Xiang#, <strong>Bao-Shan Wang</strong>#, Zhen Gao#, &amp; Peng Li#. <a href="https://doi.org/10.1007/s10915-024-02751-7">Affine-invariant WENO operator on nonuniform Cartesian mesh with application to finite volume and discontinuous Galerkin methods</a>. <em>Journal of Scientific Computing</em>, 2025, 102(2), 29. (IF: 2.8)</li>

  <li>Baifen Ren, <strong>Bao-Shan Wang</strong>, Xiangxiong Zhang, &amp; Zhen Gao*. <a href="https://doi.org/10.1016/j.camwa.2024.11.012">Positivity and bound preserving well-balanced high order compact finite difference scheme for Ripa and pollutant transport model</a>. <em>Computers and Mathematics with Applications</em>, 2024, 176, 545–563. (IF: 2.9)</li>

  <li>Zhen Gao#, Shuang Guo#, <strong>Bao-Shan Wang</strong>#, &amp; Yaguang Gu#. <a href="https://doi.org/10.4208/cicp.OA-2023-0153">High order bound- and positivity-preserving finite difference affine-invariant AWENO scheme for the five-equation model of two-medium flows</a>. <em>Communications in Computational Physics</em>, 2024, 36(3), 781–820. (IF: 2.6)</li>

  <li><strong>Bao-Shan Wang</strong> &amp; Naveen Kumar Garg*. <a href="https://doi.org/10.1016/j.compfluid.2024.106370">Third-order numerical scheme for Euler equations of gas dynamics using Jordan canonical based splitting flux</a>. <em>Computers &amp; Fluids</em>, 2024, 281, 106370. (IF: 2.5)</li>

  <li>Zhen Gao, Ya-Ru Zhao, &amp; <strong>Bao-Shan Wang</strong>*. <a href="https://doi.org/10.1016/j.aml.2024.109230">Sixth-order perturbed WENO interpolation-based AWENO and WCNS-E schemes for hyperbolic conservation laws</a>. <em>Applied Mathematics Letters</em>, 2024, 158, 109230. (IF: 2.9)</li>

  <li>Qingcheng Fu#, Zhen Gao#, Yaguang Gu#, Peng Li#, &amp; <strong>Bao-Shan Wang</strong>#. <a href="https://doi.org/10.1016/j.matcom.2024.03.007">Improved well-balanced AWENO schemes with hydrostatic reconstruction for the Euler equations under gravitational fields</a>. <em>Mathematics and Computers in Simulation</em>, 2024, 221, 260–280. (IF: 4.6)</li>

  <li>Peng Li, Tingting Li, Wai Sun Don, &amp; <strong>Bao-Shan Wang</strong>*. <a href="https://doi.org/10.1007/s10915-022-02065-6">Scale-invariant multi-resolution alternative WENO scheme for the Euler equations</a>. <em>Journal of Scientific Computing</em>, 2023, 94(1), 15. (IF: 2.5)</li>

  <li>Yinghua Wang, Wai Sun Don, &amp; <strong>Bao-Shan Wang</strong>*. <a href="https://doi.org/10.1016/j.compfluid.2022.105743">Fifth order AWENO finite difference scheme with adaptive numerical diffusion for Euler equations</a>. <em>Computers &amp; Fluids</em>, 2023, 251, 105743. (IF: 3.077)</li>

  <li>Kang-Bo Tian, Wai Sun Don, &amp; <strong>Bao-Shan Wang</strong>*. <a href="https://doi.org/10.1016/j.apnum.2023.02.004">High order WENO finite difference scheme with adaptive dual order ideal weights for hyperbolic conservation laws</a>. <em>Applied Numerical Mathematics</em>, 2023, 187, 50–70. (IF: 2.994)</li>

  <li><strong>Bao-Shan Wang</strong>, Wai Sun Don, &amp; Peng Li*. <a href="https://doi.org/10.1016/j.apnum.2022.12.019">Fifth-order well-balanced positivity-preserving finite difference AWENO scheme with hydrostatic reconstruction for hyperbolic chemotaxis models</a>. <em>Applied Numerical Mathematics</em>, 2023, 186, 41–56. (IF: 2.994)</li>

  <li><strong>Bao-Shan Wang</strong>, Wai Sun Don, Alexander Kurganov*, &amp; Yongle Liu. <a href="https://doi.org/10.1007/s42967-021-00161-2">Fifth-order A-WENO schemes based on the adaptive diffusion central-upwind Rankine-Hugoniot fluxes</a>. <em>Communications on Applied Mathematics and Computation</em>, 2023, 5, 295–314. (IF: 1.6)</li>

  <li>Yinghua Wang#, <strong>Bao-Shan Wang</strong>#, Leevan Ling#, &amp; Wai Sun Don#. <a href="https://doi.org/10.1007/s10915-022-02023-2">A time-continuous embedding method for scalar hyperbolic conservation laws on manifolds</a>. <em>Journal of Scientific Computing</em>, 2022, 93(3), 84. (IF: 2.5)</li>

  <li><strong>Bao-Shan Wang</strong>, Peng Li, &amp; Zhen Gao*. <a href="https://doi.org/10.1016/j.apnum.2022.06.006">High order well-balanced and positivity-preserving finite difference AWENO scheme with hydrostatic reconstruction for shallow water equations</a>. <em>Applied Numerical Mathematics</em>, 2022, 181, 483–502. (IF: 2.994)</li>

  <li><strong>Bao-Shan Wang</strong> &amp; Wai Sun Don*. <a href="https://doi.org/10.1016/j.apnum.2022.07.007">Affine-invariant WENO weights and operator</a>. <em>Applied Numerical Mathematics</em>, 2022, 181, 630–646. (IF: 2.994)</li>

  <li>Wai Sun Don#, Run Li#, <strong>Bao-Shan Wang</strong>#, &amp; Yinghua Wang#. <a href="https://doi.org/10.1016/j.jcp.2021.110724">A novel and robust scale-invariant WENO scheme for hyperbolic conservation laws</a>. <em>Journal of Computational Physics</em>, 2022, 448, 110724. (IF: 4.645)</li>

  <li>Peng Li#, <strong>Bao-Shan Wang</strong>#, &amp; Wai Sun Don#. <a href="https://doi.org/10.1007/s10915-021-01562-4">Sensitivity parameter-independent characteristic-wise well-balanced finite volume WENO scheme for the Euler equations under gravitational fields</a>. <em>Journal of Scientific Computing</em>, 2021, 88(2), 47. (IF: 2.843)</li>

  <li>Zhen Gao*, Qi Liu, Jan S. Hesthaven, <strong>Bao-Shan Wang</strong>, Wai Sun Don, &amp; Xiao Wen. <a href="https://doi.org/10.4208/cicp.OA-2020-0064">Non-intrusive reduced order modeling of convection dominated flows using artificial neural networks with application to Rayleigh-Taylor instability</a>. <em>Communications in Computational Physics</em>, 2021, 30(1), 97–123. (IF: 3.246)</li>

  <li><strong>Bao-Shan Wang</strong>, Wai Sun Don, Naveen Kumar Garg*, &amp; Alexander Kurganov. <a href="https://doi.org/10.1137/20M1327926">Fifth-order A-WENO finite difference schemes based on a new adaptive diffusion central numerical flux</a>. <em>SIAM Journal on Scientific Computing</em>, 2020, 42(6), A3932–A3956. (IF: 2.373)</li>

  <li>Wai Sun Don, Dong-Mei Li, Zhen Gao, &amp; <strong>Bao-Shan Wang</strong>*. <a href="https://doi.org/10.1007/s10915-020-01126-y">A characteristic-wise alternative WENO-Z finite difference scheme for solving the compressible multicomponent non-reactive flows in the overestimated quasi-conservative form</a>. <em>Journal of Scientific Computing</em>, 2020, 82(2), 27. (IF: 2.592)</li>

  <li>Zhen Gao, Li-Li Fang, <strong>Bao-Shan Wang</strong>, Yinghua Wang, &amp; Wai Sun Don*. <a href="https://doi.org/10.1016/j.compfluid.2020.104519">Seventh and ninth orders alternative WENO finite difference schemes for hyperbolic conservation laws</a>. <em>Computers &amp; Fluids</em>, 2020, 202, 104519. (IF: 3.013)</li>

  <li>Peng Li, Xiqiang Zhao, Zhen Gao*, &amp; <strong>Bao-Shan Wang</strong>. <a href="https://doi.org/10.4208/aamm.OA-2018-0264">High order hybrid weighted compact nonlinear schemes for hyperbolic conservation laws</a>. <em>Advances in Applied Mathematics and Mechanics</em>, 2020, 12(4), 972–991. (IF: 1.727)</li>

  <li>Yinghua Wang#, <strong>Bao-Shan Wang</strong>#, &amp; Wai Sun Don#. <a href="https://doi.org/10.1007/s10915-019-00998-z">Generalized sensitivity parameter free fifth order WENO finite difference scheme with Z-type weights</a>. <em>Journal of Scientific Computing</em>, 2019, 81(3), 1329–1358. (IF: 2.228)</li>

  <li><strong>Bao-Shan Wang</strong>, Peng Li, Zhen Gao, &amp; Wai Sun Don*. <a href="https://doi.org/10.1016/j.jcp.2018.07.052">An improved fifth order alternative WENO-Z finite difference scheme for hyperbolic conservation laws</a>. <em>Journal of Computational Physics</em>, 2018, 374, 469–477. (IF: 2.845)</li>

  <li><strong>Bao-Shan Wang</strong>, Wai Sun Don*, Zhen Gao, Yinghua Wang, &amp; Xiao Wen. <a href="https://doi.org/10.1137/18M1166365">Hybrid Compact-WENO finite difference scheme with radial basis function based shock detection method for hyperbolic conservation laws</a>. <em>SIAM Journal on Scientific Computing</em>, 2018, 40(6), A3699–A3714. (IF: 2.31)</li>

  <li>Wai Sun Don#, <strong>Bao-Shan Wang</strong>#, &amp; Zhen Gao#. <a href="https://doi.org/10.1007/s10915-017-0572-y">Fast iterative adaptive multi-quadric radial basis function method for edges detection of piecewise functions — I: uniform mesh</a>. <em>Journal of Scientific Computing</em>, 2018, 75(2), 1016–1039. (IF: 2.370)</li>

  <li>王立锋*, 叶文华, 陈竹, &amp; 等. <a href="https://doi.org/10.11884/HPLPB202133.200173">激光聚变内爆流体不稳定性基础问题研究进展</a>. <em>强激光与粒子束</em>, 2021, 33(1), 012001.</li>

  <li>杨洋, 曾维新, 高振, &amp; <strong>王保山</strong>*. <a href="https://doi.org/10.12288/szjs.2020.3.232">求解双曲守恒律的紧-WENO杂交格式及RBF-FD间断检测方法</a>. <em>数值计算与计算机应用</em>, 2020, 41(3), 232–245.</li>

  <li>徐捷, 高振, 曾维新, &amp; <strong>王保山</strong>*. <a href="https://doi.org/10.12288/szjs.2020.1.68">高阶驻点上精度保持的WENO有限差分格式</a>. <em>数值计算与计算机应用</em>, 2020, 41(1), 68–82.</li>

  <li><strong>王保山</strong>, 曾维新, 高振*, &amp; 陈玉虎. <a href="https://doi.org/10.16441/j.cnki.hdxb.20180179">Compact-WENO杂交格式中旋涡识别的多分辨率分析方法</a>. <em>中国海洋大学学报(自然科学版)</em>, 2018, 48(增 II), 198–202.</li>
</ol>

<h2 id="accepted">Accepted (In Press)</h2>

<ol>
  <li>Yuanyang Qiao#, Yun-Xia Liu#, <strong>Bao-Shan Wang</strong>#, &amp; Wai Sun Don#. Affine-invariant trigonometric WENO finite difference schemes for hyperbolic conservation laws. <em>Communications in Computational Physics</em>, 2025. (IF: 3.1)</li>
</ol>

<h2 id="submitted">Submitted (Under Review)</h2>

<ol>
  <li><strong>Bao-Shan Wang</strong>*. On Wave Speeds in the HLLC Riemann Solver for the Compressible Two-medium Flows. Submitted to <em>Journal of Computational Physics</em>.</li>
  <li>Shaoshuai Chu, Alexander Kurganov*, Mingye Na, <strong>Bao-Shan Wang</strong>, &amp; Ruixiao Xin. <a href="https://doi.org/10.48550/arXiv.2412.19791">Local characteristic decomposition of equilibrium variables for hyperbolic systems of balance laws</a>. Submitted to <em>Applied Numerical Mathematics</em>. Under revision.</li>
  <li>Ya-Ru Zhao, Zhen Gao, &amp; <strong>Bao-Shan Wang</strong>*. Physical-constraints-preserving path-conservative Lax-Friedrichs schemes for non-conservative two-medium six-equation model. Submitted to <em>Journal of Computational Physics</em>. Under revision.</li>
  <li>Khaled Bensayah, <strong>Bao-Shan Wang</strong>*, Jia-Hao Liu, &amp; Abdellah Hadjadj. WENO-ZKB: An improved WENO-Z+ scheme with new anti-dissipative term. Submitted to <em>Journal of Computational Physics</em>. Under revision.</li>
  <li>Qingcheng Fu, Alexander Kurganov*, &amp; <strong>Bao-Shan Wang</strong>. Local characteristic decomposition-based central-upwind flux splitting. Submitted to <em>Journal of Scientific Computing</em>. Under revision.</li>
  <li>Alex Shiu Lun Chu#, Wai Sun Don#, Leevan Ling#, &amp; <strong>Bao-Shan Wang</strong>#. Foliation structures and global flow dynamics of scalar hyperbolic conservation laws on manifolds: II. An adaptively penalized closest point embedding with a WENO finite difference scheme (AP-cp-WENO). Submitted to <em>SIAM Journal on Scientific Computing</em>.</li>
  <li>Ya-Ru Zhao, Zhen Gao, <strong>Bao-Shan Wang</strong>*, &amp; Wai Sun Don. High-order physical-constraints-preserving common-weights A-WENO scheme for non-conservative five-equation model with stiffened gas EOS. Submitted to <em>Journal of Computational Physics</em>.</li>
  <li>Jia-Hao Liu, <strong>Bao-Shan Wang</strong>, &amp; Ya-Ru Zhao*. Sixth-order AWENO schemes with adaptive linear weights for hyperbolic conservation laws. Submitted to <em>Mathematics and Computers in Simulation</em>.</li>
  <li>Changming Guo, Pengzhan Huang*, Yuanyang Qiao, <strong>Bao-Shan Wang</strong>. Accurate simulation of the granular avalanche flows by high-order positivity-preserving affine-invariant AWENO finite difference schemes. Submitted to <em>Computers and Fluids</em>.</li>
  <li>Yanping Qiu, Zhen Gao, Alexander Kurganov, <strong>Bao-Shan Wang</strong>*, &amp; Xiao Wen. <a href="https://doi.org/10.48550/arXiv.2607.09293">Fifth-order well-balanced path-conservative A-WENO scheme for the Ripa model</a>. Submitted to <em>Journal of Computational Mathematics</em>.</li>
  <li>Meifang Zhang#, <strong>Bao-Shan Wang</strong>#, Wai Sun Don#, &amp; Yuanyang Qiao#. Spatially adaptive-order bound-preserving velocity-consistent AWENO schemes for compressible two-medium flows. Submitted to <em>Journal of Scientific Computing</em>.</li>
  <li>Hai-Liang Nie, Yuanyang Qiao, <strong>Bao-Shan Wang</strong>*, &amp; Wai Sun Don. RBF-AWENO scheme with affine-invariant weights: Achieving sixth-order accuracy and multiscale robustness. Submitted to <em>Communications in Computational Physics</em>.</li>
  <li>Naveen Kumar Garg*, Jhantu Pal, &amp; <strong>Bao-Shan Wang</strong>. A Low-Dissipation LLF-Type Adaptive Central Scheme for the Compressible Euler Equations. Submitted to <em>Mathematics and Computers in Simulation</em>.</li>
  <li>Jiaxi Gu, <strong>Bao-Shan Wang</strong>*, Wai Sun Don, &amp; Jae-Hun Jung. A family of even-order central-upwind WENO schemes with averaged downwind and novel global smoothness indicators. Submitted to <em>Numerical Methods for Partial Differential Equations</em>.</li>
  <li>Jing Li, Peng Li* &amp; <strong>Bao-Shan Wang</strong>. Physical-constraints-preserving conservative-variable AWENO scheme for two-medium flows. Submitted to <em>Advances in Applied Mathematics and Mechanics</em>.</li>
  <li>邱燕萍, 高振, <strong>王保山</strong>*. 热旋转浅水波模型的五阶保平衡路径守恒特征AWENO格式. 已投稿至 <em>数值计算与计算机应用</em>.</li>
</ol>

<h2 id="preprints">In Preparation</h2>

<ol>
  <li>Shan Zhao, <strong>Bao-Shan Wang</strong>, &amp; Peng Li*. Bound-Preserving Central-Upwind Scheme for One- and Multi-Dimensional Detonation Simulations.</li>
  <li>Kang-Bo Tian, <strong>Bao-Shan Wang</strong>, &amp; Zhen Gao*. High-order well-balanced AWENO scheme for thermal rotating shallow water equations with Coriolis force.</li>
  <li>Siyuan Lang, Zhiyue Zhang, <strong>Bao-Shan Wang</strong>, &amp; Wai Sun Don. A physics-informed domain decomposition method with explicit shock tracking for 1D scalar conservation laws.</li>
  <li>Xiao-Shuo Xiang &amp; <strong>Bao-Shan Wang</strong>*. Adaptive alternative weighted essentially non-oscillatory scheme for solving Degasperis-Procesi equation.</li>
</ol>

<h2 id="books">Books &amp; Lecture Notes</h2>

<ol>
  <li>Wai Sun Don &amp; <strong>Bao-Shan Wang</strong>. <a href="https://www.researchgate.net/publication/382719342">Lecture on the High-Order WENO Scheme for Hyperbolic Conservation Laws (HKBU edition)</a>. DOI: 10.13140/RG.2.2.24752.37123/2.</li>
  <li><strong>王保山</strong>. <a href="http://www.amsc-ouc.edu.cn/Files/Research_Skills/MATLAB_Book.pdf">我的MATLAB报告</a>. 整理中.</li>
</ol>
