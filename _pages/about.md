---
permalink: /
title: ""
excerpt: ""
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
My research interests encompass a wide range of areas, including optimal guidance and control of autonomous systems. 

# 🔥 News
- I've just started my assistant professor position at Universidad Carlos III de Madrid. Feel free to reach out!
- The work "Guaranteeing Convergence in Trajectory Shaping Guidance for Impact Time Control" has been accepted by **AUTOMATICA**.

# 📝 Selected Journal Papers
<p class="section-lede">A curated view of recent work on nonlinear guidance, trajectory optimization, and learning-enabled aerospace autonomy.</p>

## Under review
<div class="paper-list">
  <article class="paper-card">
    <a class="paper-card__media" href="https://arxiv.org/abs/2606.21643">
      <img src="/images/papers/ur1.png" alt="Preview of nonlinear arrival time and angle control paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">UR1</span><span class="paper-card__tag">Trajectory shaping</span></div>
      <h3><a href="https://arxiv.org/abs/2606.21643">Nonlinear Guidance for Arrival Time and Angle Control Using Trajectory Shaping</a></h3>
      <p class="paper-card__meta"><strong>Wang K</strong>. Under review.</p>
      <p class="paper-card__summary">This work shapes the look angle with a fourth-order polynomial so a fixed-wing UAV can meet both arrival time and arrival angle requirements. A two-stage solver supplies a warm start and then refines the coupled nonlinear guidance parameters, improving feasibility in highly nonlinear cases.</p>
    </div>
  </article>

  <article class="paper-card">
    <div class="paper-card__media">
      <img src="/images/papers/ur2.svg" alt="Placeholder preview for low-thrust rendezvous guidance paper" loading="lazy">
    </div>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">UR2</span><span class="paper-card__tag">Low-thrust rendezvous</span></div>
      <h3>Learning-Based Minimum-Time Optimal Guidance for Low-Thrust Spacecraft Rendezvous</h3>
      <p class="paper-card__meta"><strong>Wang K</strong>. Under review.</p>
      <p class="paper-card__summary">This study targets minimum-time rendezvous guidance for low-thrust spacecraft, where onboard computation and nonlinear dynamics make direct optimal control challenging. The learning-based formulation is intended to approximate optimal guidance decisions quickly enough for closed-loop use.</p>
    </div>
  </article>

  <article class="paper-card">
    <a class="paper-card__media" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6662558">
      <img src="/images/papers/ur3.svg" alt="Placeholder preview for adjoint control transformation paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">UR3</span><span class="paper-card__tag">Indirect method</span></div>
      <h3><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6662558">Physics-Informed Trajectory Optimization for Terminal Guidance Based on Adjoint Control Transformation</a></h3>
      <p class="paper-card__meta">Ding C, <strong>Wang K</strong>, Guo Y, et al. Under review.</p>
      <p class="paper-card__summary">The paper uses adjoint control transformation to estimate difficult costate initial values for terminal-guidance TPBVPs. A physics-informed neighborhood search further refines analytical initial accelerations, reducing solve time compared with random initialization.</p>
    </div>
  </article>
</div>

## 2026
<div class="paper-list">
  <article class="paper-card">
    <div class="paper-card__media">
      <img src="/images/papers/j14.svg" alt="Placeholder preview for predictor-corrector arrival time control paper" loading="lazy">
    </div>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J14</span><span class="paper-card__tag">Arrival-time control</span></div>
      <h3>Predictor-Corrector Nonlinear Arrival Time Control Guidance under Time-Varying Velocity</h3>
      <p class="paper-card__meta"><strong>Wang K</strong>, Xu Y. <em>Guidance, Navigation, and Control</em>, 2026.</p>
      <p class="paper-card__summary">This work studies nonlinear arrival-time guidance when the vehicle speed changes during flight. A predictor-corrector structure updates the guidance command online so timing accuracy is preserved under time-varying velocity.</p>
    </div>
  </article>

  <article class="paper-card">
    <a class="paper-card__media" href="https://arxiv.org/abs/2503.15362">
      <img src="/images/papers/j13.png" alt="Preview of nonlinear optimal impact time control with field-of-view constraint paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J13</span><span class="paper-card__tag">Optimal guidance</span></div>
      <h3><a href="https://arxiv.org/abs/2503.15362">Nonlinear Optimal Guidance for Impact Time Control with Field-of-View Constraints</a></h3>
      <p class="paper-card__meta">Lu F, Chen Z, <strong>Wang K</strong>. <em>AIAA Journal of Guidance, Control, and Dynamics</em>, 2026.</p>
      <p class="paper-card__summary">The paper converts field-of-view constrained impact-time guidance into a parameterized optimal-control problem and uses generated extremal trajectories to train a neural network. The resulting law produces near-optimal commands very quickly while respecting the seeker field-of-view constraint.</p>
    </div>
  </article>

  <article class="paper-card">
    <a class="paper-card__media" href="https://www.sciencedirect.com/science/article/pii/S0005109826002918">
      <img src="/images/papers/j12.svg" alt="Placeholder preview for trajectory shaping convergence paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J12</span><span class="paper-card__tag">Convergence guarantee</span></div>
      <h3><a href="https://www.sciencedirect.com/science/article/pii/S0005109826002918">Guaranteeing Convergence in Trajectory Shaping Guidance for Impact Time Control</a></h3>
      <p class="paper-card__meta"><strong>Wang K</strong>, Ding C, Wei Z, Wang P, Chen Z. <em>Automatica</em>, 2026.</p>
      <p class="paper-card__summary">This work strengthens trajectory-shaping impact-time guidance by deriving explicit bounds on the guidance gain and a capture region. Those analytical conditions rule out high-effort roots and make the numerical solution more reliable before flight.</p>
    </div>
  </article>

  <article class="paper-card">
    <a class="paper-card__media" href="https://www.sciencedirect.com/science/article/pii/S1270963826005110">
      <img src="/images/papers/j11.svg" alt="Placeholder preview for look-angle-shaped impact time control paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J11</span><span class="paper-card__tag">Field-of-view</span></div>
      <h3><a href="https://www.sciencedirect.com/science/article/pii/S1270963826005110">Look-Angle-Shaped Impact Time Control Guidance with Field-of-View Constraints</a></h3>
      <p class="paper-card__meta"><strong>Wang K</strong>, Wei Z, Wang P. <em>Aerospace Science and Technology</em>, 2026.</p>
      <p class="paper-card__summary">The look angle is shaped with a bounded hyperbolic tangent function, so the FOV constraint is built into the guidance profile without switching logic. The paper also derives practical impact-time bounds and a fast initialization scheme for the guidance gain.</p>
    </div>
  </article>

  <article class="paper-card">
    <a class="paper-card__media" href="https://www.sciencedirect.com/science/article/pii/S0273117726002231">
      <img src="/images/papers/j10.png" alt="Preview of coordinated parafoil landing paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J10</span><span class="paper-card__tag">Parafoil systems</span></div>
      <h3><a href="https://www.sciencedirect.com/science/article/pii/S0273117726002231">Coordinated Guidance and Control for Multiple Parafoil System Landing</a></h3>
      <p class="paper-card__meta">Wei Z, <strong>Wang K</strong>, Shao Z, Biegler LT. <em>Advances in Space Research</em>, 2026.</p>
      <p class="paper-card__summary">This paper formulates multi-parafoil landing as a coordinated trajectory optimization and control problem. Landing-point assignment, collision-free replanning, nonlinear MPC, and moving-horizon correction are combined to support safe and efficient group landing.</p>
    </div>
  </article>

  <article class="paper-card">
    <a class="paper-card__media" href="https://www.sciencedirect.com/science/article/pii/S0094576526000950?via%3Dihub">
      <img src="/images/papers/j9.svg" alt="Placeholder preview for certified-stability spacecraft rendezvous paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J9</span><span class="paper-card__tag">Certified learning</span></div>
      <h3><a href="https://www.sciencedirect.com/science/article/pii/S0094576526000950?via%3Dihub">Learning-Based Optimal Guidance for Spacecraft Close-Proximity Operations with Certified Stability</a></h3>
      <p class="paper-card__meta"><strong>Wang K</strong>, Armellin R, Evans A, et al. <em>Acta Astronautica</em>, 2026.</p>
      <p class="paper-card__summary">A neural Lyapunov-function framework is combined with supervised learning to produce time- and fuel-optimal rendezvous guidance with stability certificates. The method jointly learns the certificate and control policy, including cases with bang-bang fuel-optimal behavior.</p>
    </div>
  </article>
</div>

## 2025
<div class="paper-list">
  <article class="paper-card">
    <a class="paper-card__media" href="https://doi.org/10.1016/j.automatica.2025.112500">
      <img src="/images/papers/j8.png" alt="Preview of nonlinear optimal guidance with impact time and angle constraints paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J8</span><span class="paper-card__tag">Impact time and angle</span></div>
      <h3><a href="https://doi.org/10.1016/j.automatica.2025.112500">Nonlinear Optimal Guidance with Constraints on Impact Time and Impact Angle</a></h3>
      <p class="paper-card__meta">Wu F, Chen Z, Shao X, <strong>Wang K</strong>. <em>Automatica</em>, 2025, 181, 112500.</p>
      <p class="paper-card__summary">This work treats simultaneous impact-time and impact-angle control as a nonlinear minimum-effort guidance problem. Pontryagin-based parameterization and scaling properties make it possible to train a compact neural network that generates locally optimal commands in milliseconds.</p>
    </div>
  </article>

  <article class="paper-card">
    <a class="paper-card__media" href="https://ieeexplore.ieee.org/document/10926912/">
      <img src="/images/papers/j7.svg" alt="Placeholder preview for acceleration-constrained impact angle guidance paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J7</span><span class="paper-card__tag">Acceleration constraints</span></div>
      <h3><a href="https://ieeexplore.ieee.org/document/10926912/">Nonlinear Optimal Impact Angle Control Guidance Considering Acceleration Constraints</a></h3>
      <p class="paper-card__meta"><strong>Wang K</strong>, Lu F, Chen Z. <em>IEEE Transactions on Aerospace and Electronic Systems</em>, 2025, 61(4), 8907-8921.</p>
      <p class="paper-card__summary">The article designs impact-angle guidance for varying-speed interceptors with maximum-acceleration and zero-terminal-acceleration constraints. Regularization, saturation, and a neural-network implementation are combined with feedback guidance for practical real-time use.</p>
    </div>
  </article>
</div>

## 2024
<div class="paper-list">
  <article class="paper-card">
    <a class="paper-card__media" href="https://ieeexplore.ieee.org/document/10623330/">
      <img src="/images/papers/j6.png" alt="Preview of physics-informed indirect method paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J6</span><span class="paper-card__tag">Trajectory optimization</span></div>
      <h3><a href="https://ieeexplore.ieee.org/document/10623330/">A Physics-Informed Indirect Method for Trajectory Optimization</a></h3>
      <p class="paper-card__meta"><strong>Wang K</strong>, Lu F, Chen Z, et al. <em>IEEE Transactions on Aerospace and Electronic Systems</em>, 2024, 60(6), 9179-9192.</p>
      <p class="paper-card__summary">The paper narrows the indirect-method shooting space by embedding physical information about flight time, costates, and terminal control. This physics-informed initialization makes soft-landing trajectory optimization faster and more robust, especially when paired with homotopy.</p>
    </div>
  </article>

  <article class="paper-card">
    <a class="paper-card__media" href="https://linkinghub.elsevier.com/retrieve/pii/S0273117724007154">
      <img src="/images/papers/j5.png" alt="Preview of fuel-optimal powered descent guidance paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J5</span><span class="paper-card__tag">Powered descent</span></div>
      <h3><a href="https://linkinghub.elsevier.com/retrieve/pii/S0273117724007154">Fuel-Optimal Powered Descent Guidance for Lunar Pinpoint Landing Using Neural Networks</a></h3>
      <p class="paper-card__meta"><strong>Wang K</strong>, Chen Z, Jun Li. <em>Advances in Space Research</em>, 2024, 74(10), 5006-5022.</p>
      <p class="paper-card__summary">This work uses PMP-derived structure to generate optimal powered-descent training data without repeated numerical optimization. Neural networks then approximate steering angle, time of flight, and a regularized switching function for fuel-optimal lunar landing guidance.</p>
    </div>
  </article>

  <article class="paper-card">
    <a class="paper-card__media" href="https://linkinghub.elsevier.com/retrieve/pii/S0094576524000341">
      <img src="/images/papers/j4.svg" alt="Placeholder preview for solar sailcraft real-time optimal control paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J4</span><span class="paper-card__tag">Solar sailing</span></div>
      <h3><a href="https://linkinghub.elsevier.com/retrieve/pii/S0094576524000341">Real-Time Optimal Control for Attitude-Constrained Solar Sailcrafts via Neural Networks</a></h3>
      <p class="paper-card__meta"><strong>Wang K</strong>, Lu F, Chen Z, et al. <em>Acta Astronautica</em>, 2024, 216, 446-458.</p>
      <p class="paper-card__summary">This paper develops real-time optimal control for solar-sail transfers while respecting attitude constraints. It preprocesses discontinuous optimal commands and uses cooperating neural networks to recover the original optimal sail attitude online.</p>
    </div>
  </article>

  <article class="paper-card">
    <a class="paper-card__media" href="https://www.worldscientific.com/doi/10.1142/S2737480724500110">
      <img src="/images/papers/j3.png" alt="Preview of lunar vertical landing trajectory planning paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J3</span><span class="paper-card__tag">Lunar landing</span></div>
      <h3><a href="https://www.worldscientific.com/doi/10.1142/S2737480724500110">Fuel-Optimal Trajectory Planning for Lunar Vertical Landing</a></h3>
      <p class="paper-card__meta"><strong>Wang K</strong>, Chen Z, Jun Li. <em>Guidance, Navigation, and Control</em>, 2024, 04(02), 2450011.</p>
      <p class="paper-card__summary">The vertical landing requirement is reformulated as a final steering-angle constraint and embedded through a regularized cost functional. A transformation and bisection procedure then support indirect shooting for fuel-optimal lunar vertical landing trajectories.</p>
    </div>
  </article>
</div>

## 2023
<div class="paper-list">
  <article class="paper-card">
    <a class="paper-card__media" href="https://linkinghub.elsevier.com/retrieve/pii/S0005109823000869">
      <img src="/images/papers/j2.png" alt="Preview of curvature-bounded path elongation paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J2</span><span class="paper-card__tag">Path planning</span></div>
      <h3><a href="https://linkinghub.elsevier.com/retrieve/pii/S0005109823000869">Elongation of Curvature-Bounded Path</a></h3>
      <p class="paper-card__meta">Chen Z, <strong>Wang K</strong>, Shi H. <em>Automatica</em>, 2023, 151, 110936.</p>
      <p class="paper-card__summary">The paper establishes explicit, numerically verifiable conditions for whether a curvature-bounded path of a desired length exists between two oriented points. It also gives elongation strategies and demonstrates cooperative timing for multiple Dubins vehicles.</p>
    </div>
  </article>
</div>

## 2022
<div class="paper-list">
  <article class="paper-card">
    <a class="paper-card__media" href="https://arc.aiaa.org/doi/10.2514/1.G006666">
      <img src="/images/papers/j1.png" alt="Preview of impact-time constrained nonlinear optimal guidance paper" loading="lazy">
    </a>
    <div class="paper-card__body">
      <div class="paper-card__topline"><span class="paper-card__id">J1</span><span class="paper-card__tag">Impact-time guidance</span></div>
      <h3><a href="https://arc.aiaa.org/doi/10.2514/1.G006666">Nonlinear Optimal Guidance for Intercepting Stationary Targets with Impact-Time Constraints</a></h3>
      <p class="paper-card__meta"><strong>Wang K</strong>, Chen Z, Han Wang, et al. <em>AIAA Journal of Guidance, Control, and Dynamics</em>, 2022, 45(9), 1614-1626.</p>
      <p class="paper-card__summary">This work builds a real-time nonlinear optimal guidance law for intercepting a stationary target at a prescribed time. PMP-based parameterization generates training data for a feedforward network that maps state and time-to-go directly to the optimal command.</p>
    </div>
  </article>
</div>

# 📝 Selected Conference Papers
- [C6] **Wang K**. Trajectory Shaping Guidance for Field-of-View Constrained Impact Angle Control[C], 2026 EuroGNC.
- [C5] **Wang K**, Chen Z, Lu F, et al. Neural-Network-Based Optimal Guidance for Lunar Vertical Landing [C], **2024 IEEE 18th International Conference on Control & Automation (ICCA)**.
- [C4] Ma, H., Chen, Z., **Wang, K**. Learning-Based Optimal Guidance for Hypersonic Reentry Using a Barrier Function [C].**2024 IEEE 18th International Conference on Control & Automation (ICCA)**.
- [C3] Lu, F., Chen, Z., **Wang, K**. Learning-based Optimal Entry Guidance with Path Constraints [C].**2024 IEEE 18th International Conference on Control & Automation (ICCA)**.
- [C2]**Wang K**, Chen Z, et al. A New Smoothing Technique for Bang-Bang Optimal Control Problems [C]//**AIAA SciTech 2024 Forum**. 2024: 0727. 
- [C1] **Wang K**, Chen Z, Li J. Real-Time Generation of Optimal Flight Trajectories via Shallow Neural Network [C]//International Conference on Autonomous Unmanned Systems. Singapore: Springer Singapore, 2021: 1668-1676.

# 🎖 Selected Honors and Awards
- National Scholarship for Doctoral Graduate Students, Ministry of Education of the People's Republic of China. 
- "Rising Star" Scholarship for Overseas Graduate Research, Zhejiang University. 
- "Golden Years" Overseas Exchange Scholarship, Zhejiang University. Visited Politecnico di Milano.
- Scholarship for Incoming Freshmen, Zhejiang University. 
- National Scholarship for Graduate Students, Ministry of Education of the People's Republic of China. 

# 📖 Educations
- Ph.D., Aerospace Engineering, Zhejiang University, Hangzhou, China. <!-- Supervised by Prof. [Zheng Chen](https://person.zju.edu.cn/0019048) --> 
- Visiting Ph.D. student, The University of Auckland, Auckland, New Zealand. <!--Supervised by Prof. [Roberto Armellin](https://profiles.auckland.ac.nz/roberto-armellin))--> 

# 📚 Review and Journal Activities
- Reviewer for multiple top-tier journals, such as
- **Automatica**
- **Journal of Guidance, Control, and Dynamics**
- **IEEE T-AES**
- **Acta Astronautica**
- **Advances in Space Research**
- **Space: Science & Technology**
- **Aerospace Science and Technology**
- Young Editorial Board Member for **IET Cyber-Systems and Robotics**
- Young Editorial Board Member for **Unmanned Systems Technology**

# 💻 Skills
- Matlab/Simulink, Python, C/C++
- Chinese, English
  
# 🌍 Visitors Info
 <a href="https://info.flagcounter.com/LJvB"><img src="https://s01.flagcounter.com/count2/LJvB/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_10/viewers_0/labels_0/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a>

