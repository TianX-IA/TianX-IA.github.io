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

Hi, I'm Tian Xia, a master's student in CSE at Harvard University. I recently graduated from the University of Michigan, Ann Arbor with triple majors in Honors Math, Honors CS, and DS. I previously worked as a research intern at [SafoLab](https://xiaocw11.github.io/) and [SLED lab](https://sled.eecs.umich.edu/). I am deeply passionate about modeling concepts in mathematical language and examining them from different perspectives. My main excitement lies in *computer vision*, *machine learning* and *robotics*. Outside of research, I’m an avid gamer, enjoy long walks, and love flying to different cities.


# Research

My research spans *computer vision*, *generative modeling*, and *multimodal learning*. I am interested in how models represent visual and spatial structure, and how we can adapt them to new tasks with useful supervision and feedback. My work includes semantic-aware 3D reconstruction, consistent video generation, and prompt optimization for multimodal clinical tasks.

More recently, I have been studying how optimization objectives and evaluation criteria shape model behavior, from ranking-aware prompt search to reflective learning in LLM agents. My current interests include:

- *Visual and spatial understanding*: Connecting images, language, and 3D representations for perception and embodied systems.
- *Generative modeling*: Improving video consistency and studying how synthetic data supports downstream visual learning.
- *Prompt optimization and evaluation*: Designing feedback and selection objectives that reflect the capabilities we want models and agents to learn.

# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/ranking-pe.png' alt="Ranking-PE overview of multimodal clinical diagnosis and ranking-aware evaluation" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Ranking-PE: Ranking-Aware Prompt Optimization for Multimodal Clinical Diagnosis](https://ranking-pe.github.io/)

**Tian Xia**, Minghao Liu, Yiqing Liang, Laixi Shi, Jiayun Wang

Ranking-aware prompt optimization that aligns prompt search, reflective feedback, and final selection with AUROC for multimodal clinical diagnosis.

\[[**Project**](https://ranking-pe.github.io/)\]\[[**Paper**](https://ranking-pe.github.io/assets/paper.pdf)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">3D-LLM/VLA @ CVPR 2025</div><img src='images/Sab3r.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[SAB3R: Semantic-Augmented Backbone in 3D Reconstruction](https://uva-computer-vision-lab.github.io/sab3r/)

Xuweiyi Chen\*, **Tian Xia**\*, Sihan XU, Jianing Yang, Joyce Chai, Zezhou Cheng

\[[**Project**](https://uva-computer-vision-lab.github.io/sab3r/)\]\[[**Arxiv**](https://www.arxiv.org/abs/2506.02112)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR</div><img src='images/UniCtrl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[UniCtrl: Improving the Spatiotemporal Consistency of Text-to-Video Diffusion Models via Training-Free Unified Attention Control](https://openreview.net/forum?id=x2uFJ79OjK)

**Tian Xia**\*, Xuweiyi Chen\*, Sihan Xu

\[[**Project**](https://unified-attention-control.github.io/)\]\[[**Arxiv**](https://arxiv.org/abs/2403.02332)\]\[[**Code**](https://github.com/XuweiyiChen/UniCtrl)\]
</div>
</div>

# Honors and Awards
- *2025:* Outstanding Achievement in Mathematics Awards 
- *2024:* Evelyn O. Bychinsky Awards
- *2024:* James B. Angell Scholar
- *2023, 2024:* M.S. Keeler Department of Mathematics Merit Scholarships
- *2022, 2023:* University Honors

# Educations
- *2025.08 - now*, S.M. in Computational Science and Engineering, Harvard University
- *2022.09 - 2025.05*, B.S. in Honors Mathematics, Honors Computer Science and Data Science, University of Michigan, Ann Arbor

# Talks
- *2024.10*, Open Vocabulary 3D Querying with Unposed Images @ SLED.
  
<span class='anchor' id='side-projects'></span>

# Course Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CS 1440R / 2440R · 2026</div><img src='images/cs1440-frontier.png' alt="Frontier selection and feedback in reflective prompt evolution" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Frontier Construction Shapes Reflective Prompt Evolution in LLM Negotiation](assets/course-projects/cs1440-report.pdf)

Manasa Bala, Chong Zhao, **Tian Xia**

A study of how Pareto frontier construction shapes prompt selection and reflective feedback, comparing flat, per-instance, and per-axis selection in buyer-seller negotiations.

\[[**Report**](assets/course-projects/cs1440-report.pdf)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AC 209B / CS 1090B · 2026</div><img src='images/artist-authorship.png' alt="Effect of real and synthetic training-data mixing on artist attribution" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Generative Data Augmentation for Artist Authorship Attribution](assets/course-projects/cs1090b-report.pdf)

Yiqiao Huang, Lixuan Wei, Ruyi Yang, **Tian Xia**

SDXL adaptation with LoRA and ControlNet for artist attribution, studying how the balance of real and synthetic training examples affects performance on underperforming classes.

\[[**Report**](assets/course-projects/cs1090b-report.pdf)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CS 2050 · 2026</div><img src='assets/course-projects/cs2050/hero_pattern.png' alt="Pattern produced by the Gray-Scott reaction-diffusion simulation" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Parallel Gray-Scott Reaction-Diffusion](assets/course-projects/cs2050/index.html)

**Tian Xia**

Serial C++, OpenMP, MPI, CUDA, and mpi4py implementations of the same reaction-diffusion system, with correctness checks, scaling experiments, and CPU profiling.

\[[**Report**](assets/course-projects/cs2050/index.html)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AM 205 · 2025</div><img src='images/am205-least-squares.png' alt="Gauss-Newton and Levenberg-Marquardt convergence from different initial parameters" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Nonlinear Least Squares: Gauss-Newton and Levenberg-Marquardt](https://github.com/TianX-IA/AM205Project)

A computational study of damped-oscillation parameter estimation, examining sensitivity to initialization, ill-conditioning, and measurement noise.

\[[**Code**](https://github.com/TianX-IA/AM205Project)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EECS 442 Course Projects</div><img src='images/442.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Rethink the Noise Prior of Initialization Gap in Video Diffusion Models](EECS_442_project.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EECS 486 Course Projects</div><img src='images/486.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[What is on People’s Minds?](EECS_486_project.pdf)

\[[Poster](EECS_486_poster.pdf)\]

</div>
</div>

# Other Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TransferWiki</div><img src='images/transferwiki.com_.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[TransferWiki](https://transferwiki.com/) - Collaborator

TransferWiki is a platform created to assist students from mainland China who are planning to transfer to universities abroad, particularly in the United States, Canada, and the United Kingdom. This platform addresses the challenges and information asymmetry faced by students during the transfer process.
  
</div>
</div> 

<div style="display: none;">
<a href="https://clustrmaps.com/site/1c3xy"  title="ClustrMaps"><img src="//www.clustrmaps.com/map_v2.png?d=KGoDhh2MGlq2_aRXVHwc96dxN6LKB_mtZnT3ozSASwQ&cl=ffffff" /></a>
</div>
