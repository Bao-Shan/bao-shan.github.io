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
      <a class="home-button" href="./CV_Baoshan_WANG.pdf">CV</a>
    </p>
  </div>
  <div class="home-hero__image">
    <img src="/images/profile.jpg" alt="Bao-Shan Wang" onerror="this.style.display='none'">
  </div>
</section>

<!-- ===== ABOUT ===== -->
<span class="anchor" id="about-me"></span>
<h1 id="about-me">About Me</h1>

<p>I am an Associate Professor at the School of Mathematical Sciences, Ocean University of China. I received my Ph.D. in Computational Mathematics from the same university in 2022, under the supervision of Prof. Wai Sun Don.</p>

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
      <h3>Associate Professor</h3>
      <p class="academic-timeline__institution">School of Mathematical Sciences, Ocean University of China, Qingdao, China</p>
    </div>
  </article>
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">Aug 2022 – Sep 2024</div>
    <div class="academic-timeline__content">
      <h3>Postdoctoral Researcher</h3>
      <p class="academic-timeline__institution">School of Mathematical Sciences, Ocean University of China, Qingdao, China</p>
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
      <p class="academic-timeline__institution">Ocean University of China, Qingdao, China</p>
      <p>Supervisor: Prof. Wai Sun Don.</p>
      <p>Thesis: <em>Physical-Constraints-Preserving High-Order WENO Schemes</em>.</p>
    </div>
  </article>
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">Sep 2015 – Jun 2018</div>
    <div class="academic-timeline__content">
      <h3>M.Sc. in Computational Mathematics</h3>
      <p class="academic-timeline__institution">Ocean University of China, Qingdao, China</p>
      <p>Supervisors: Prof. Zhen Gao &amp; Prof. Wai Sun Don.</p>
      <p>Thesis: <em>Radial Basis Function Based Shock Detection Algorithm and Its Application in High-Order Hybrid Schemes</em>.</p>
    </div>
  </article>
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">Aug 2011 – Jun 2015</div>
    <div class="academic-timeline__content">
      <h3>B.Sc. in Mathematics and Applied Mathematics</h3>
      <p class="academic-timeline__institution">Ocean University of China, Qingdao, China</p>
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
      <p><strong>Pohang University of Science and Technology</strong> | Department of Mathematics</p>
      <p>Hosts: Prof. Jae-Hun Jung &amp; Dr. Jiaxi Gu.</p>
    </div>
  </article>
  <article class="visiting-list__item">
    <p class="visiting-list__date">Nov 2024 / Nov 2025</p>
    <div>
      <h3>Visiting Scholar</h3>
      <p><strong>Hong Kong Baptist University</strong> | Department of Mathematics</p>
      <p>Hosts: Prof. Leevan Ling (Department Head) &amp; Prof. Wai Sun Don.</p>
    </div>
  </article>
  <article class="visiting-list__item">
    <p class="visiting-list__date">May 2024</p>
    <div>
      <h3>Visiting Scholar</h3>
      <p><strong>Hong Kong University of Science and Technology</strong> | Department of Mathematics</p>
      <p>Host: Prof. Zhichao Peng.</p>
    </div>
  </article>
  <article class="visiting-list__item">
    <p class="visiting-list__date">Mar 2024 – May 2024</p>
    <div>
      <h3>Visiting Scholar</h3>
      <p><strong>Southern University of Science and Technology</strong> | Department of Mathematics</p>
      <p>Host: Prof. Alexander Kurganov.</p>
    </div>
  </article>
  <article class="visiting-list__item">
    <p class="visiting-list__date">Oct 2023 – Jan 2024</p>
    <div>
      <h3>Visiting Scholar</h3>
      <p><strong>Hong Kong Baptist University</strong> | Department of Mathematics</p>
      <p>Hosts: Prof. Leevan Ling (Department Head) &amp; Prof. Wai Sun Don.</p>
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
  <li><strong>Outstanding Graduate Students of Ocean University of China (Top 10, 2021).</li>
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
      <h3>NSFC (PI, RMB 300,000)</h3>
      <p class="academic-timeline__institution">Time-Continuous Closest Point Method for Hyperbolic Conservation Laws on Manifolds</p>
    </div>
  </article>
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">2025–2027</div>
    <div class="academic-timeline__content">
      <h3>Startup Fund from OUC (PI, RMB 300,000)</h3>
      <p class="academic-timeline__institution">High-Order Physical-Constraints-Preserving Numerical Methods for Multi-Material Flow Models under Extreme Conditions</p>
    </div>
  </article>
  <article class="academic-timeline__item">
    <div class="academic-timeline__date">2026–2028</div>
    <div class="academic-timeline__content">
      <h3>Shandong Provincial Qingchuang Science and Technology Project (PI)</h3>
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
  <li><strong>Other:</strong> Founder of WeChat public account "台劳公式" (3,100+ followers).</li>
</ul>

<!-- ===== PUBLICATIONS ===== -->
<span class="anchor" id="publications"></span>
<h1 id="publications">Publications</h1>

<p>(* denotes corresponding author; # denotes equal contribution; IF = Impact Factor)</p>

<h2 id="journal-articles">Journal of Computational Physics (JCP)</h2>

<ol>
  <li>Changming Guo, <strong>Bao-Shan Wang</strong>#, Wai Sun Don#, &amp; Yuanyang Qiao#. <a href="https://doi.org/10.1016/j.jcp.2026.115049">High-order physical-constraints-preserving velocity-consistent schemes for compressible multicomponent five-equation model with the Mie-Gruneisen equation of state</a>. <em>Journal of Computational Physics</em>, 2026, 563, 115049. (IF: 3.8)</li>

  <li>Ya-Ru Zhao, Zhen Gao, &amp; <strong>Bao-Shan Wang</strong>*. <a href="https://doi.org/10.1016/j.jcp.2025.114409">Fifth-order equilibrium-preserving path-conservative characteristic-wise AWENO scheme for one-fluid two-temperature Euler model</a>. <em>Journal of Computational Physics</em>, 2026, 544, 114409. (IF: 3.8)</li>

  <li>Changming Guo, Yuanyang Qiao, Wai Sun Don, &amp; <strong>Bao-Shan Wang</strong>*. <a href="https://doi.org/10.1016/j.jcp.2025.114149">A family of bound-preserving velocity-consistent schemes for two-medium γ-based model with stiffened gas</a>. <em>Journal of Computational Physics</em>, 2025, 538, 114149. (IF: 3.8)</li>

  <li>Wai Sun Don#, Run Li#, <strong>Bao-Shan Wang</strong>#, &amp; Yinghua Wang#. <a href="https://doi.org/10.1016/j.jcp.2021.110724">A novel and robust scale-invariant WENO scheme for hyperbolic conservation laws</a>. <em>Journal of Computational Physics</em>, 2022, 448, 110724. (IF: 4.645)</li>

  <li><strong>Bao-Shan Wang</strong>, Peng Li, Zhen Gao, &amp; Wai Sun Don*. <a href="https://doi.org/10.1016/j.jcp.2018.07.052">An improved fifth order alternative WENO-Z finite difference scheme for hyperbolic conservation laws</a>. <em>Journal of Computational Physics</em>, 2018, 374, 469–477. (IF: 2.845)</li>
</ol>

<h2 id="siam">SIAM Journal on Scientific Computing (SISC)</h2>

<ol>
  <li><strong>Bao-Shan Wang</strong>, Wai Sun Don, Naveen Kumar Garg*, &amp; Alexander Kurganov. <a href="https://doi.org/10.1137/20M1327926">Fifth-order A-WENO finite difference schemes based on a new adaptive diffusion central numerical flux</a>. <em>SIAM Journal on Scientific Computing</em>, 2020, 42(6), A3932–A3956. (IF: 2.373)</li>

  <li><strong>Bao-Shan Wang</strong>, Wai Sun Don*, Zhen Gao, Yinghua Wang, &amp; Xiao Wen. <a href="https://doi.org/10.1137/18M1166365">Hybrid Compact-WENO finite difference scheme with radial basis function based shock detection method for hyperbolic conservation laws</a>. <em>SIAM Journal on Scientific Computing</em>, 2018, 40(6), A3699–A3714. (IF: 2.31)</li>
</ol>

<h2 id="accepted">Accepted (In Press)</h2>

<ol>
  <li>Yuanyang Qiao#, Yun-Xia Liu#, <strong>Bao-Shan Wang</strong>#, &amp; Wai Sun Don#. Affine-invariant trigonometric WENO finite difference schemes for hyperbolic conservation laws. <em>Communications in Computational Physics</em>, 2025. (IF: 3.1)</li>
</ol>

<h2 id="submitted">Submitted (Under Review)</h2>

<ol>
  <li><strong>Bao-Shan Wang</strong>*. On Wave Speeds in the HLLC Riemann Solver for the Compressible Two-medium Flows. Submitted to <em>Journal of Computational Physics</em>.</li>

  <li>Ya-Ru Zhao, Zhen Gao, &amp; <strong>Bao-Shan Wang</strong>*. Physical-constraints-preserving path-conservative Lax-Friedrichs schemes for non-conservative two-medium six-equation model. Submitted to <em>Journal of Computational Physics</em>. Under revision.</li>

  <li>Khaled Bensayah, <strong>Bao-Shan Wang</strong>*, Jia-Hao Liu, &amp; Abdellah Hadjadj. WENO-ZKB: An improved WENO-Z+ scheme with new anti-dissipative term. Submitted to <em>Journal of Computational Physics</em>. Under revision.</li>

  <li>Alex Shiu Lun Chu#, Wai Sun Don#, Leevan Ling#, &amp; <strong>Bao-Shan Wang</strong>#. Foliation structures and global flow dynamics of scalar hyperbolic conservation laws on manifolds: II. An adaptively penalized closest point embedding with a WENO finite difference scheme (AP-cp-WENO). Submitted to <em>SIAM Journal on Scientific Computing</em>.</li>

  <li>Ya-Ru Zhao, Zhen Gao, <strong>Bao-Shan Wang</strong>*, &amp; Wai Sun Don. High-order physical-constraints-preserving common-weights A-WENO scheme for non-conservative five-equation model with stiffened gas EOS. Submitted to <em>Journal of Computational Physics</em>.</li>
</ol>

<p>For a complete list of publications, please visit my <a href="https://scholar.google.com/citations?user=TiPSLVsAAAAJ">Google Scholar</a> or <a href="https://www.researchgate.net/profile/Baoshan-Wang">ResearchGate</a>.</p>
