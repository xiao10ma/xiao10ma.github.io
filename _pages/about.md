---
permalink: /
title: ""
excerpt: "PhD Student @ FDU"
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

I am a PhD student at Fudan University and Shanghai Innovation Institute, advised by [Prof. Li Zhang](https://lzrobots.github.io/). Prior to that, I received my Bachelor's degree from Sun Yat-sen University. My research focuses on post-training embodied AI models, particularly through DAgger and reinforcement learning, as well as tactile perception and learning.

I work closely with my senior labmates [Junzhe Jiang](https://selfspin.github.io/) and [Jingyu Li](https://sii-whaleice.github.io/).

# 🔥 News

- *2026.09*: &nbsp;🎉🎉 TacPAC is now available on [arXiv](https://arxiv.org/abs/2609.05266).
- *2026.07*: &nbsp;🎉🎉 DriveWeaver has been accepted by ECCV 2026.
- *2026.05*: &nbsp;🎉🎉 MoLA has been accepted by ICML 2026.
- *2025.06*: &nbsp;🎉🎉 BézierGS has been accepted by ICCV 2025.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><a href='https://arxiv.org/pdf/2609.05266'><img src='images/pipeline/tacpac.png' alt="TacPAC pipeline" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[TacPAC: Tactile Prediction and Real-Time Action Correction in World-Action Models for Contact-Rich Manipulation](https://arxiv.org/abs/2609.05266)

**Zipei Ma**, Xiaofei Wei, Junzhe Jiang, Shunlin Lu, Li Zhang

[**Code**](https://github.com/LogosRoboticsGroup/TacPAC)

- TL;DR: We introduce TacPAC, which uses cached tactile predictions to interpret incoming touch and correct unexecuted actions in real time, improving average success from 22% to 64% across five contact-rich real-robot tasks.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report 2026</div><a href='https://arxiv.org/pdf/2607.23783'><img src='images/pipeline/n0-twam.png' alt="N0-TWAM teaser" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[$\mathcal{N}_0$-TWAM: Scaling Tactile-Native World Action Model for Contact-Rich Manipulation](https://arxiv.org/abs/2607.23783v1)

NeoteAI Team & Fudan TEAI Team

[**Project**](https://research.neoteai.com/n0-twam/) [**Code**](https://github.com/neoteai/N0-TWAM)

- TL;DR: We introduce $\mathcal{N}_0$-TWAM, a tactile-native world-action model that jointly predicts future vision, touch, and actions, enabling stronger contact-rich manipulation through large-scale visuo-tactile pretraining.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report 2026</div><a href='https://research.neoteai.com/assets/n0-foundation-report.pdf'><img src='images/pipeline/n0-foundation.png' alt="N0-Foundation teaser" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[$\mathcal{N}_0$-Foundation: Towards the Age of Tactile Intelligence](https://research.neoteai.com/assets/n0-foundation-report.pdf)

NeoteAI Team & Fudan TEAI Team

[**Project**](https://research.neoteai.com/n0-foundation/) [**Dataset**](https://huggingface.co/datasets/NeoteAIEmbodied/OpenNeoData)

- TL;DR: We present $\mathcal{N}_0$-Foundation, a tactile-centric foundation that unifies scalable sensing hardware, large-scale multimodal data, transferable tactile representations, and standardized real-world and simulated evaluation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026</div><a href='https://arxiv.org/pdf/2606.31918'><img src='images/pipeline/driveweaver.png' alt="DriveWeaver pipeline" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[DriveWeaver: Point-Conditioned Video Inpainting for Controllable Vehicle Insertion in Autonomous Driving Simulation](https://arxiv.org/pdf/2606.31918)

Junzhe Jiang, **Zipei Ma**, Zijie Pan, Li Zhang†

[**Code**](https://github.com/LogosRoboticsGroup/DriveWeaver)

- TL;DR: We propose DriveWeaver, a point-cloud-conditioned video inpainting framework that inserts controllable, temporally consistent vehicles and extracts their 3D Gaussian representations for real-time autonomous driving simulation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><a href='https://arxiv.org/pdf/2606.15869'><img src='images/pipeline/metis.png' alt="Metis framework" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Metis: A Generalizable and Efficient World-Action Model for Autonomous Driving and Urban Navigation](https://arxiv.org/abs/2606.15869)

Jingyu Li\*, Zhe Liu\*, Dongnan Hu, Junjie Wu, **Zipei Ma**, Wenxiao Wu, Chao Han, Zhihui Hao, Zhikang Liu, Kun Zhan, Jiankang Deng, Xiatian Zhu, Li Zhang†

[**Code**](https://github.com/LogosRoboticsGroup/Metis)

- TL;DR: We introduce Metis, an efficient world-action model that decouples video generation and action prediction through specialized transformer experts and asymmetric attention, retaining world-model supervision during training while bypassing video generation at inference.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><a href='https://arxiv.org/pdf/2605.12167'><img src='images/pipeline/MoLA.png' alt="MoLA pipeline" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[From Imagined Futures to Executable Actions: Mixture of Latent Actions for Robot Manipulation](https://arxiv.org/pdf/2605.12167)

Yajie Li\*, Bozhou Zhang\*, Chun Gu, **Zipei Ma**, Jiahui Zhang, Jiankang Deng, Xiatian Zhu, Li Zhang

[**Project**](https://logosroboticsgroup.github.io/MoLA/) [**Code**](https://github.com/LogosRoboticsGroup/MoLA)

- TL;DR: We introduce MoLA, which transforms imagined future videos into executable representations through a mixture of pretrained inverse dynamics models, achieving consistent gains in simulation and real-world robot manipulation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><a href='https://arxiv.org/pdf/2511.20633'><img src='images/pipeline/prophrl.png' alt="ProphRL thumbnail" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Reinforcing Action Policies by Prophesying](https://arxiv.org/pdf/2511.20633)

Jiahui Zhang\*, Ze Huang\*, Chun Gu, **Zipei Ma**, Li Zhang†

[**Project**](https://logosroboticsgroup.github.io/ProphRL/) [**Code**](https://github.com/LogosRoboticsGroup/ProphRL)

- TL;DR: We introduce ProphRL, which learns a reusable action-to-video world model and a flow-aware RL post-training strategy to improve VLA policies efficiently, delivering strong gains in both simulation and real-robot tasks.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><a href='https://arxiv.org/pdf/2506.22099'><img src='images/pipeline/beziergs.png' alt="BézierGS pipeline" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[BézierGS: Dynamic Urban Scene Reconstruction with Bézier Curve Gaussian Splatting](https://arxiv.org/pdf/2506.22099)

**Zipei Ma**\*, Junzhe Jiang\*, Yurui Chen, Li Zhang†

[**Code**](https://github.com/fudan-zvg/BezierGS)

- TL;DR: We propose a method that models object motion using Bézier curves, achieving accurate reconstruction and effective foreground-background separation.

</div>
</div>

# 🎓 Academic Service

- *Conference Reviewer*: ICML, AAAI



# 📖 Educations

- *2025.06 - Present*, Fudan University & SII
- *2021.09 - 2025.06*, Sun Yat-sen University

# 🤣 Hobbies

- 🏸 Badminton, ⚽️ Football(Visca el Barça! 💙❤️)
- 🎮 Games(Soulslike, Multiplayer...)
- 🎬 Movies, 🎵 Music
