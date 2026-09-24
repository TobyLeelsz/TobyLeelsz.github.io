---
permalink: /
title: ""
excerpt: "Shangzhe Li is a Ph.D. student at UNC Chapel Hill working on reinforcement learning, imitation learning, and world models."
author_profile: false
academic_home: true
redirect_from:
  - /about/
  - /about.html
---
<div class="home-layout" markdown="1">
<aside id="about-me" class="home-hero" aria-label="Profile">
  <div class="home-hero__profile">
    <img src="{{ site.author.avatar | relative_url }}" alt="Shangzhe Li’s illustrated avatar" width="176" height="176">
  </div>
  <div class="home-hero__content">
    <p class="home-hero__eyebrow">Computer Science · Ph.D. Student</p>
    <h1>Shangzhe Li</h1>
    <p class="home-hero__chinese" lang="zh">李尚哲</p>
    <p class="home-hero__affiliation">University of North Carolina<br>at Chapel Hill</p>
    <p class="home-hero__location">Chapel Hill, North Carolina</p>
    <div class="home-hero__actions">
      <a href="mailto:{{ site.author.email }}"><i class="fas fa-envelope" aria-hidden="true"></i><span>{{ site.author.email }}</span></a>
      <a href="{{ site.author.googlescholar }}"><i class="fas fa-graduation-cap" aria-hidden="true"></i><span>Google Scholar</span></a>
      <a href="https://github.com/{{ site.author.github }}"><i class="fab fa-github" aria-hidden="true"></i><span>GitHub</span></a>
    </div>
    <p class="home-hero__research">Reinforcement learning<br>Imitation learning<br>World models &amp; robot learning</p>
  </div>
</aside>

<div class="home-main" markdown="1">
<section id="about" class="site-section intro-section" markdown="1">
<h2>About me</h2>
Hello! I’m Shangzhe Li (李尚哲), a second-year Ph.D. student at UNC Chapel Hill, where I’m fortunate to be advised by [Prof. Weitong Zhang](https://zeroweight.github.io/). I also collaborate with [Prof. Hao Su](https://www.haosu.ai/) and [Dr. Zhiao Huang](https://sites.google.com/view/zhiao-huang) at [Sudo AI](https://www.sudo.ai/). Previously, I had the privilege of working with [Prof. Marco Caccamo](https://rtsl.cps.mw.tum.de/personal_page/mcaccamo/) and [Prof. Nils Thuerey](https://ge.in.tum.de/about/n-thuerey/) at the Technical University of Munich, as well as [Prof. Xinhua Zhang](https://www.cs.uic.edu/~zhangx/) at the University of Illinois Chicago.

Outside research, I enjoy aviation, physics, and mathematics. I’m originally from Guangzhou.
</section>

<section id="research" class="site-section research-section" markdown="1">
<h2>Research interests</h2>
I study reinforcement learning and imitation learning, connecting theoretical foundations with algorithms for foundation models and robotic decision-making.

<div class="interest-grid">
  <article class="interest-card"><span class="interest-number" aria-hidden="true">01</span><h3>Learning to act</h3><p>Deep and model-based reinforcement learning; adversarial imitation learning in high-dimensional environments.</p></article>
  <article class="interest-card"><span class="interest-number" aria-hidden="true">02</span><h3>Foundations of learning</h3><p>Theoretical foundations of reinforcement and imitation learning that inform more effective algorithms.</p></article>
  <article class="interest-card"><span class="interest-number" aria-hidden="true">03</span><h3>Models &amp; embodiment</h3><p>Alignment, distillation, and reasoning for foundation models; world models for robotic manipulation and locomotion.</p></article>
</div>
</section>

<section id="news" class="site-section news-section" markdown="1">
<h2>News</h2>
<ul class="news-list">
<li><time datetime="2026-09">2026.09</time><div markdown="1">
Two papers have been accepted by NeurIPS 2026.
</div></li>
<li><time datetime="2026-09">2026.09</time><div markdown="1">
One paper has been accepted by IROS 2026 Workshop on Physical World Models for Scaling Embodied AI for **Oral Presentation**.
</div></li>
<li><time datetime="2026-04">2026.04</time><div markdown="1">
One paper has been accepted by Transactions on Machine Learning Research.
</div></li>
<li><time datetime="2026-03">2026.03</time><div markdown="1">
One paper has been accepted by ICLR 2026 Workshop on AI with Recursive Self-Improvement.
</div></li>
</ul>
<details class="news-archive" markdown="1">
<summary>Earlier news</summary>
<ul class="news-list">
<li><time datetime="2026-03">2026.03</time><div markdown="1">
One paper has been accepted by ICLR 2026 Workshop on Real-World Constrained and Preference-Aligned Generative Models.
</div></li>
<li><time datetime="2026-01">2026.01</time><div markdown="1">
One paper has been accepted by ICLR 2026.
</div></li>
<li><time datetime="2025-11">2025.11</time><div markdown="1">
One paper has been accepted by AAAI 2026.
</div></li>
<li><time datetime="2025-09">2025.09</time><div markdown="1">
One paper has been accepted by NeurIPS 2025 Workshop on Embodied World Models.
</div></li>
<li><time datetime="2025-05">2025.05</time><div markdown="1">
One paper has been accepted by ICML 2025.
</div></li>
<li><time datetime="2025-03">2025.03</time><div markdown="1">
I'll be joining UNC Chapel Hill for my PhD, advised by Prof. Weitong Zhang!
</div></li>
<li><time datetime="2025-03">2025.03</time><div markdown="1">
One paper has been accepted by ICLR 2025 Workshop on World Models.
</div></li>
<li><time datetime="2024-03">2024.03</time><div markdown="1">
Summer intern offer received from [Su Lab](https://cseweb.ucsd.edu/~haosu/), UCSD! See you in San Diego in summer if everything goes smoothly!
</div></li>
<li><time datetime="2023-09">2023.09</time><div markdown="1">
&nbsp;🎉🎉 Homepage has been set up.
</div></li>
</ul>
</details>
</section>

<div class="papers-overview">
  <nav class="paper-nav" aria-label="Paper categories">
    <a href="#publications">Publications</a>
    <a href="#preprints">Preprints</a>
    <a href="#workshop-papers">Workshop papers</a>
  </nav>
  <p class="contribution-note">† Equal contribution</p>
</div>

<section id="publications" class="site-section publications-section">
  <div class="section-heading"><h2>Publications</h2><span class="section-count">{{ site.data.papers | where: "category", "publications" | size }}</span></div>
  {% include paper-list.html category="publications" %}
</section>

<section id="preprints" class="site-section publications-section">
  <div class="section-heading"><h2>Preprints</h2><span class="section-count">{{ site.data.papers | where: "category", "preprints" | size }}</span></div>
  {% include paper-list.html category="preprints" %}
</section>

<section id="workshop-papers" class="site-section publications-section">
  <div class="section-heading"><h2>Workshop papers</h2><span class="section-count">{{ site.data.papers | where: "category", "workshops" | size }}</span></div>
  {% include paper-list.html category="workshops" %}
</section>

<div class="academic-details" markdown="1">
<section id="service" class="site-section service-section" markdown="1">
<h2>Professional service</h2>
<h3>Conference reviewer / program committee</h3>
AAAI 2026/2027, ICLR 2026, ICRA 2026, ICML 2026, NeurIPS 2026.

<h3>Journal reviewer</h3>
Transactions on Machine Learning Research (TMLR).
</section>

<section id="teaching" class="site-section teaching-section">
<h2>Teaching</h2>
<div class="teaching-item"><span>Spring 2026 · UNC Chapel Hill</span><h3>DATA 522</h3><p>Practical Deep Learning Systems<br><span>Teaching Assistant</span></p></div>
<div class="teaching-item"><span>Fall 2025 · UNC Chapel Hill</span><h3>DATA 110</h3><p>Introduction to Data Science<br><span>Teaching Assistant</span></p></div>
</section>
</div>

<section id="blog" class="site-section blog-section" markdown="1">
<div class="section-heading"><h2>Writing</h2><span class="writing-language">Articles in Chinese</span></div>
<details class="writing-group" markdown="1">
<summary>Physics<span>23 articles</span></summary>

- [**Propagation of electromagnetic waves in the presence of conductors**](https://zhuanlan.zhihu.com/p/487555515)
- [**Solution of Laplace's equation in spherical coordinate system**](https://zhuanlan.zhihu.com/p/492694563)
- [**Gauge transformations and D'Alembert's equation**](https://zhuanlan.zhihu.com/p/504982231)
- [**Maxwell stress tensor and electromagnetic field momentum**](https://zhuanlan.zhihu.com/p/523698037)
- [**Electrodynamics of tensor forms**](https://zhuanlan.zhihu.com/p/538907023)
- [**Geodesic equations, affine connections and covariant differentiation**](https://zhuanlan.zhihu.com/p/599077467)
- [**Intrinsic time variations, geodesic equations advanced**](https://zhuanlan.zhihu.com/p/599930752)
- [**Riemann curvature tensor**](https://zhuanlan.zhihu.com/p/600891458)
- [**Curvature advanced and Bianchi Constant Equation**](https://zhuanlan.zhihu.com/p/601088640)
- [**Energy-Momentum tensor and Einstein field equations**](https://zhuanlan.zhihu.com/p/601255696)
- [**Relativistic electrodynamics and electromagnetic analogies**](https://zhuanlan.zhihu.com/p/602635631)
- [**Harmonic coordinate condition**](https://zhuanlan.zhihu.com/p/604933950)
- [**Energy, momentum and angular momentum of a gravitational field**](https://zhuanlan.zhihu.com/p/611102483)
- [**Schwarzschild metric and Schwarzschild black hole**](https://zhuanlan.zhihu.com/p/612420413)
- [**Gravitational wave**](https://zhuanlan.zhihu.com/p/614730295)
- [**Gravitational wave advanced**](https://zhuanlan.zhihu.com/p/615282349)
- [**Universal definition of the action and energy tensor**](https://zhuanlan.zhihu.com/p/619484924)
- [**Energy-Momentum tensor advanced and gravitational action**](https://zhuanlan.zhihu.com/p/621155312)
- [**Killing vector fields and maximal symmetric spaces**](https://zhuanlan.zhihu.com/p/624578802)
- [**Lie group and Lie algebra**](https://zhuanlan.zhihu.com/p/644154704)
- [**Quantum Lorentz transformations and Poincaré algebra**](https://zhuanlan.zhihu.com/p/645056327)
- [**Single particle state**](https://zhuanlan.zhihu.com/p/645264336)
- [**Parity and time reversal**](https://zhuanlan.zhihu.com/p/692194960)

</details>
<details class="writing-group" markdown="1">
<summary>Mathematics<span>7 articles</span></summary>

- [**Dual spaces and tensors**](https://zhuanlan.zhihu.com/p/540551745)
- [**Symmetry of the tensor**](https://zhuanlan.zhihu.com/p/543078969)
- [**Continuous and discrete time Fourier transforms**](https://zhuanlan.zhihu.com/p/606937411)
- [**Laplace transform and Z-transform**](https://zhuanlan.zhihu.com/p/611844650)
- [**Primary fiber bundles (I)**](https://zhuanlan.zhihu.com/p/644632269)
- [**Primary fiber bundles (II)**](https://zhuanlan.zhihu.com/p/656135139)
- [**Connections on primary fibre bundles**](https://zhuanlan.zhihu.com/p/676335305)

</details>
<details class="writing-group" markdown="1">
<summary>Convex Optimization<span>2 articles</span></summary>

- [**Optimality theory for unconstrained problems**](https://zhuanlan.zhihu.com/p/612089283)
- [**Duality theory**](https://zhuanlan.zhihu.com/p/615771472)

</details>
</section>

<footer class="site-footer-card">
  <p>© {{ site.time | date: "%Y" }} {{ site.author.name }}</p>
  <p>Special thanks to <span lang="zh">五月</span> for the Kurisu avatar artwork.</p>
</footer>
</div>
</div>
