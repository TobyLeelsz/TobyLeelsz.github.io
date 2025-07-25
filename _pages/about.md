---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hello! I’m Shangzhe Li, a Ph.D. student at UNC Chapel Hill, where I'm fortunate to work under the guidance of [Prof. Weitong Zhang](https://zeroweight.github.io/). I also collaborate closely with [Prof. Hao Su](https://cseweb.ucsd.edu/~haosu/) at the University of California, San Diego. Previously, I’ve had the opportunity to work with [Prof. Marco Caccamo](https://rtsl.cps.mw.tum.de/personal_page/mcaccamo/) and [Prof. Nils Thuerey](https://ge.in.tum.de/about/n-thuerey/) at the Technical University of Munich, as well as with [Prof. Xinhua Zhang](https://www.cs.uic.edu/~zhangx/) at the University of Illinois at Chicago.

I'm passionate about aviation, Physics, and Mathematics, and I’m pursuing my studies in Artificial Intelligence. My hometown is Guangzhou. In my free time, I enjoy live streaming on Bilibili, sharing insights on Zhihu, and indulging in my love for anime.  

My research interests lie broadly in the fields of reinforcement learning and imitation learning, with a focus on both algorithmic design and practical applications:

- **Deep Reinforcement Learning**: I’m interested in developing novel reinforcement learning algorithms powered by deep neural networks to tackle complex decision-making problems. Lately, I’ve been particularly focused on model-based RL.

- **Imitation Learning**: I explore new approaches to imitation learning, especially adversarial imitation learning in complex, high-dimensional environments. I’m also excited about leveraging large foundation models within imitation learning frameworks.

- **Theoretical Foundations of RL/IL**: I aim to better understand the theoretical underpinnings of reinforcement and imitation learning, with the goal of using theory to inform and inspire more effective algorithmic designs.

- **Applications in LLM Post-training and Robot Learning**: I’m interested in applying RL to enhance large language model post-training (e.g., alignment, distillation, and reasoning), as well as to solve challenging robotic control problems in manipulation and locomotion.

# 🔥 News
- *2025.05*, One paper has been accepted by ICML 2025.
- *2025.03*, I'll be joining UNC Chapel Hill for my PhD, advised by Prof. Weitong Zhang!
- *2025.03*, One paper has been accepted by ICLR 2025 Workshop on World Models.
- *2024.03*, Summer intern offer received from [Su Lab](https://cseweb.ucsd.edu/~haosu/), UCSD! See you in San Diego in summer if everything goes smoothly!
- *2023.09*, &nbsp;🎉🎉 Homepage has been set up.

# 📝 Publications
†: Equal contributions.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='/images/teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Language Model Distillation: A Temporal Difference Imitation Learning Perspective](https://arxiv.org/abs/2505.20335)

Zishun Yu †, **Shangzhe Li** †, Xinhua Zhang

-  Motivated by the observation that a small number of top tokens contribute the majority of the total probability mass, we proposed a top-p TD learning framework that operates over a top-p candidate action subset. This framework is, in principle, plug-and-play and can be integrated into any TD-based IRL algorithm. We demonstrated its practicality through a concrete implementation of top-p IQL and showed its empirical performance gains.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='/images/pipeline_cdred.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Coupled Distributional Random Expert Distillation for World Model Online Imitation Learning](https://arxiv.org/abs/2505.02228)

**Shangzhe Li**, Zhiao Huang, Hao Su

- We propose a novel approach for world model-based online imitation learning, featuring an innovative reward model formulation. Unlike traditional adversarial approaches that may introduce instability during training, our reward model is grounded in density estimation for both expert and behavioral state-action distributions. This formulation enhances stability while maintaining high performance. Our model demonstrates expert-level proficiency across various tasks in multiple benchmarks, including DMControl, Meta-World, and ManiSkill2. Furthermore, it consistently retains stable performance throughout long-term online training. With its robust reward modeling and stability, our approach has the potential to tackle complex real-world robotics control tasks, where reliability and adaptability are crucial.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='/images/compressed_iqmpc_final.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reward-free World Models for Online Imitation Learning](https://arxiv.org/abs/2410.14081)

**Shangzhe Li**, Zhiao Huang, Hao Su

[**Code**](https://github.com/TobyLeelsz/iqmpc)

- We propose an online imitation learning approach that utilizes reward-free world models to address tasks in complex environments. By incorporating latent planning and dynamics learning, our model can have a deeper understanding of intricate environment dynamics. We demonstrate stable, expert-level performance on challenging tasks, including dexterous hand manipulation and high-dimensional locomotion control.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='/images/Combined_Bridge_DTS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Augmenting Offline Reinforcement Learning with State-only Interactions](https://arxiv.org/abs/2402.00807)

**Shangzhe Li**, Xinhua Zhang

- We proposed a novel data augmentation method DITS for offline RL, where state-only interactions are available with the environment. The generator based on conditional diffusion models allows high-return trajectories to be sampled, and the stitching algorithm blends them with the original ones. The resulting augmented dataset is shown to significantly boost the performance of base RL methods.
</div>
</div>

# 📝 Blog Articles
*Notice: All of the articles here are written in Chinese.* 

**Physics Part:**
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

**Mathematics Part:**
- [**Dual spaces and tensors**](https://zhuanlan.zhihu.com/p/540551745)
- [**Symmetry of the tensor**](https://zhuanlan.zhihu.com/p/543078969)
- [**Continuous and discrete time Fourier transforms**](https://zhuanlan.zhihu.com/p/606937411)
- [**Laplace transform and Z-transform**](https://zhuanlan.zhihu.com/p/611844650)
- [**Primary fiber bundles (I)**](https://zhuanlan.zhihu.com/p/644632269)
- [**Primary fiber bundles (II)**](https://zhuanlan.zhihu.com/p/656135139)
- [**Connections on primary fibre bundles**](https://zhuanlan.zhihu.com/p/676335305)

**Convex Optimization Part:**
- [**Optimality theory for unconstrained problems**](https://zhuanlan.zhihu.com/p/612089283)
- [**Duality theory**](https://zhuanlan.zhihu.com/p/615771472)
