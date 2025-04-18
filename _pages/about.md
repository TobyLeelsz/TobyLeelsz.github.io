---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hello! I'm Shangzhe Li, an undergraduate student from South China University of Technology and an incoming Ph.D. student at UNC Chapel Hill, where I’m fortunate to be advised by [Prof. Weitong Zhang](https://zeroweight.github.io/). Previously, I have worked with [Prof. Hao Su](https://cseweb.ucsd.edu/~haosu/) at the University of California, San Diego, [Prof. Marco Caccamo](https://rtsl.cps.mw.tum.de/personal_page/mcaccamo/) at the Technical University of Munich, and [Prof. Xinhua Zhang](https://www.cs.uic.edu/~zhangx/) at the University of Illinois at Chicago.  

I'm passionate about aviation, Physics, and Mathematics, and I’m pursuing my studies in Artificial Intelligence. My hometown is Guangzhou. In my free time, I enjoy live streaming on Bilibili, sharing insights on Zhihu, and indulging in my love for anime.  

My research interest includes reinforcement learning, robot learning and world models.

*Links to my social media:*
- [**Bilibili**](https://space.bilibili.com/183461839)
- [**Zhihu**](https://www.zhihu.com/people/dva13304)

# 🔥 News
- *2025.03*, I'll be joining UNC Chapel Hill for my PhD, advised by Prof. Weitong Zhang!
- *2025.03*, One paper has been accepted by ICLR 2025 Workshop on World Models.
- *2024.03*, Summer intern offer received from [Su Lab](https://cseweb.ucsd.edu/~haosu/), UCSD! See you in San Diego in summer if everything goes smoothly!
- *2023.09*, &nbsp;🎉🎉 Homepage has been set up.

# 📝 Publications
- **Coupled Distributional Random Expert Distillation for World Model Online Imitation Learning**

  Author: **Shangzhe Li**, Zhiao Huang, Hao Su

  Main Contribution: We propose a novel approach for world model-based online imitation learning, featuring an innovative reward model formulation. Unlike traditional adversarial approaches that may introduce instability during training, our reward model is grounded in density estimation for both expert and behavioral state-action distributions. This formulation enhances stability while maintaining high performance. Our model demonstrates expert-level proficiency across various tasks in multiple benchmarks, including DMControl, Meta-World, and ManiSkill2. Furthermore, it consistently retains stable performance throughout long-term online training. With its robust reward modeling and stability, our approach has the potential to tackle complex real-world robotics control tasks, where reliability and adaptability are crucial.

  ![demo_IQMPC](/images/pipeline_cdred.png)
  **Preprint**.
  
- **Reward-free World Models for Online Imitation Learning** [[Preprint]](https://arxiv.org/abs/2410.14081)

  Author: **Shangzhe Li**, Zhiao Huang, Hao Su

  Main Contribution: We propose an online imitation learning approach that utilizes reward-free world models to address tasks in complex environments. By incorporating latent planning and dynamics learning, our model can have a deeper understanding of intricate environment dynamics. We demonstrate stable, expert-level performance on challenging tasks, including dexterous hand manipulation and high-dimensional locomotion control.

  ![demo_IQMPC](/images/combined_vertical_video.gif)
  **ICLR 2025 Workshop on World Models**.
  
- **Augmenting Offline Reinforcement Learning with State-only Interactions** [[Preprint]](https://arxiv.org/abs/2402.00807)

  Author: **Shangzhe Li**, Xinhua Zhang
  
  Main Contribution: We proposed a novel data augmentation method DITS for offline RL,
where state-only interactions are available with the environment.
The generator based on conditional diffusion models allows high-return trajectories to be sampled,
and the stitching algorithm blends them with the original ones.
The resulting augmented dataset is shown to significantly boost the performance of base RL methods.
  
  ![pipeline_TSKD](/images/Bridge_1.png)
  **Preprint**.
  
- **Data-efficient Offline Domain Adaptation for Model-free Agents using Model-based Trajectory Stitching**

  Author: **Shangzhe Li**, Hongpeng Cao, Marco Caccamo
  
  Main Contribution: This work improves the sampling efficiency for policy adaptation in the deployment environment by stitching the offline experiences with newly collected few-shot experiences from the new environment. The proposed stitching algorithm incorporates the dynamics information of the true-MDP with the new dataset, meanwhile increasing the data diversity and de-correlating the newly collected data. The experiments on two cases show that the pre-trained policies are improved more efficiently with higher accumulated reward by using the stitched dataset than direct fine-tuning using raw data.
  
  ![pipeline_TSDA](/images/pipeline_TSDA.png)
  **Preprint**.

# 🎖 Honors and Awards
- *2022* First Prize, Asia and Pacific Mathematical Contest in Modeling(APMCM) 
- *2022* Second Prize, National Contemporary Undergraduate Mathematical Contest in Modeling(CUMCM)
- *2022* Successful Participant, Mathematical Contest in Modeling(MCM)
- *2023* Successful Participant, Mathematical Contest in Modeling(MCM)
- *2021* Second Prize, Baidu “Paddle Paddle” Cup
- *2022* First Prize, Taihu Academic Innovation Scholarship (CNY 8000)
- *2022* Second Prize, Taihu Science Innovation Scholarship (CNY 5000)

# 📖 Educations
- *2023.10 - 2024.07*, Exchange student, Technical University of Munich.
- *2021.09 - now*, Undergraduate student, South China University of Technology.
- *2018.09 - 2021.06*, High school student (Physics Olympiad), Affiliated High School of South China Normal University.

**Current GPA:** 3.87/4.00  **Current Rank:** 3/80

# 💬 Talks
- *2023.09*, Invited by the Artificial Intelligence Association of South China University of Technology, Application of Diffusion Model on Offline Reinforcement Learning.
  Link: [**Application of Diffusion Model on Offline Reinforcement Learning**](https://www.bilibili.com/video/BV1C8411v7QD/)
- *2023.12*, Performed presentation in the Doctoral Seminar of Thuerey's Group from Technical University of Munich, Application of Diffusion Model on Offline Reinforcement Learning.

# 💻 Internships and Research Experience
- *2022.09 - 2023.04*, **Undergraduate Research**, Neural Networks Compression and Acceleration Research. Supervisor: [**Prof. Ye Liu, South China University of Technology**](https://www2.scut.edu.cn/ft/2021/1102/c29779a449612/page.htm).
- *2023.05 - 2024.01*, **Research Intern (Remote)**, Application of Diffusion Model on Offline Reinforcement Learning. Supervisor: [**Prof. Xinhua Zhang, University of Illinois Chicago**](https://www.cs.uic.edu/~zhangx/).
- *2023.10 - 2024.06*, **Research Intern**, Research on the Control Approach for Two-way Coupled Fluid Simulation. Supervisor: [**Prof. Nils Thuerey, Technical University of Munich**](https://ge.in.tum.de/about/n-thuerey/), Mentor: [**Patrick Schnell**](https://ge.in.tum.de/about/patrick-schnell/).
- *2024.01 - 2024.09*, **Research Intern**, Research on the Fast Adaptation Methods on Reinforcement Learning. Supervisor: [**Prof. Marco Caccamo, Technical University of Munich**](https://rtsl.cps.mw.tum.de/personal_page/mcaccamo/), Collaborator: [**Hongpeng Cao**](https://rtsl.cps.mw.tum.de/view_member?id=15).
- *2024.02 - now*, **Research Intern (Remote)**, Distillation in LLMs via Reinforcement Learning Algorithms. Supervisor: [**Prof. Xinhua Zhang, University of Illinois Chicago**](https://www.cs.uic.edu/~zhangx/), Collaborator: [**Zishun Yu**](https://zishun.me/).
- *2024.06 - now*, **Research Intern**, Research in World Models and Inverse Reinforcement Learning. Supervisor: [**Prof. Hao Su, University of California, San Diego**](https://cseweb.ucsd.edu/~haosu/), Mentor: [**Zhiao Huang**](https://sites.google.com/view/zhiao-huang).

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
