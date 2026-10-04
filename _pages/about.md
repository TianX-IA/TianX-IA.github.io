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

Hi, I'm Tian Xia, a master's student in CSE at Harvard University, working with Prof. [Qianqian Wang](https://qianqianwang68.github.io/). Previously, I graduated from the University of Michigan, Ann Arbor, with majors in Honors Math, Honors CS, and DS, where I worked with Prof. Joyce Chai at the [SLED Lab](https://sled.eecs.umich.edu/). Outside of research, I enjoy gaming, long walks, and exploring new cities.


# Research

My research interests focus on *3D understanding*, *generative AI*, and *embodied agents*, emphasizing scalable systems and cross-modal representations. I aim to develop machine learning systems that integrate vision, language, and spatial information to understand and model the physical world, enabling self-evolving agents to improve through interaction and feedback.

Over time, my interests have expanded to encompass a broader range of topics, including computer vision, multimodal learning, and robotics. My current focus areas include:

- *Visual and spatial understanding*: 3D reconstruction, recognition, and motion understanding.
- *Generative modeling*: Video generation and cross-modal synthesis.
- *Multimodal and self-evolving agents*: Multimodal reasoning and strategy refinement through feedback.

# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026 (Spotlight)</div><img src='images/mose3-figure1.png' alt="MoSE3 Figure 1: dense SE(3) predictions for rigid, articulated, and non-rigid motion" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[MoSE3: Learning World-Space SE(3) at Every Pixel](https://mose3-tracker.github.io/)

Jiahuan Cheng\*, Zhiyi Li\*, **Tian Xia**\*, Ruojin Cai, Yilun Du, Qianqian Wang

\[[**Project**](https://mose3-tracker.github.io/)\]\[[**Paper**](https://mose3-tracker.github.io/paper.pdf)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/ranking-pe.png' alt="Ranking-PE overview of multimodal clinical diagnosis and ranking-aware evaluation" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Ranking-PE: Ranking-Aware Prompt Optimization for Multimodal Clinical Diagnosis](https://ranking-pe.github.io/)

**Tian Xia**, Minghao Liu, Yiqing Liang, Laixi Shi, Jiayun Wang

\[[**Project**](https://ranking-pe.github.io/)\]\[[**Arxiv**](https://arxiv.org/abs/2609.40361)\]\[[**Paper**](https://arxiv.org/pdf/2609.40361)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">3D-LLM/VLA @ CVPR 2025</div><img src='images/Sab3r.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[SAB3R: Semantic-Augmented Backbone in 3D Reconstruction](https://uva-computer-vision-lab.github.io/sab3r/)

Xuweiyi Chen\*, **Tian Xia**\*, Sihan XU, Jianing Yang, Joyce Chai, Zezhou Cheng

\[[**Project**](https://uva-computer-vision-lab.github.io/sab3r/)\]\[[**Arxiv**](https://www.arxiv.org/abs/2506.02112)\]\[[**Code**](https://github.com/UVA-Computer-Vision-Lab/sab-3r)\]\[[**Poster**](/assets/posters/sab3r-poster.pdf)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR 2024</div><img src='images/UniCtrl.png' alt="sym" width="100%"></div></div>
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
  
<span class='anchor' id='course-projects'></span>

# Side Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CS 1440R Course Projects</div><img src='images/cs1440-frontier.png' alt="Frontier selection and feedback in reflective prompt evolution" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Frontier Construction Shapes Reflective Prompt Evolution in LLM Negotiation](assets/course-projects/cs1440-report.pdf)

\[[**Paper**](assets/course-projects/cs1440-report.pdf)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AC 209B Course Projects</div><img src='images/artist-augmentation-pipeline.png' alt="Artist-specific data augmentation pipeline using SDXL, LoRA, and ControlNet" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Generative Data Augmentation for Artist Authorship Attribution](assets/course-projects/cs1090b-report.pdf)

\[[**Paper**](assets/course-projects/cs1090b-report.pdf)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CS 2050 Course Projects</div><img src='assets/course-projects/cs2050/hero_pattern.png' alt="Pattern produced by the Gray-Scott reaction-diffusion simulation" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Parallel Gray-Scott Reaction-Diffusion](assets/course-projects/cs2050/index.html)

\[[**Report**](assets/course-projects/cs2050/index.html)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AM 205 Course Projects</div><img src='images/am205-least-squares.png' alt="Gauss-Newton and Levenberg-Marquardt convergence from different initial parameters" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Nonlinear Least Squares: Gauss-Newton and Levenberg-Marquardt](assets/course-projects/am205-paper.pdf)

\[[**Paper**](assets/course-projects/am205-paper.pdf)\]\[[**Code**](https://github.com/TianX-IA/AM205Project)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EECS 545 Course Projects</div><img src='images/eecs545-attention.png' alt="Attention manipulation pipeline for hallucination mitigation in vision-language models" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Attention Manipulation for Hallucination Mitigation](assets/course-projects/eecs545-paper.pdf)

\[[**Paper**](assets/course-projects/eecs545-paper.pdf)\]\[[**Poster**](assets/course-projects/eecs545-poster.pdf)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EECS 442 Course Projects</div><img src='images/442.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Rethink the Noise Prior of Initialization Gap in Video Diffusion Models](EECS_442_project.pdf)

\[[**Paper**](EECS_442_project.pdf)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EECS 486 Course Projects</div><img src='images/486.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[What is on People’s Minds?](EECS_486_project.pdf)

\[[**Paper**](EECS_486_project.pdf)\]\[[**Poster**](EECS_486_poster.pdf)\]

</div>
</div>

<span class='anchor' id='other-projects'></span>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TransferWiki</div><img src='images/transferwiki.com_.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[TransferWiki](https://transferwiki.com/) - Collaborator
  
</div>
</div> 

<div style="display: none;">
<a href="https://clustrmaps.com/site/1c3xy"  title="ClustrMaps"><img src="//www.clustrmaps.com/map_v2.png?d=KGoDhh2MGlq2_aRXVHwc96dxN6LKB_mtZnT3ozSASwQ&cl=ffffff" /></a>
</div>
