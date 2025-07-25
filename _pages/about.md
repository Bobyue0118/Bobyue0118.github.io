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

Hi👋, I’m currently a first-year PhD student at [the School of Data Science](https://sds.cuhk.edu.cn/en), [The Chinese University of Hong Kong, Shenzhen (CUHK-SZ)](https://www.cuhk.edu.cn/en), supervised by Prof. [Guiliang Liu](https://guiliang.me/). Before that, I received both M.Eng degrees (2024) and B.Eng (2021) at [the Department of Automation](https://automation.sjtu.edu.cn/), [Shanghai Jiao Tong University (SJTU)](https://en.sjtu.edu.cn/).

My research interest includes:
- Robot Learning and Optimization in Embodied AI
- Embodied Large Language Model Reasoning
- Inverse Constrained Reinforcement Learning / Inverse Constraint Learning

For discussions or collaborations, feel free to drop me an email!


# 🔥 News
- *2025.05* &nbsp; 🎉🎉 One paper was accepted to **ICML 2025**.
- *2025.01* &nbsp; 🎉🎉 Three papers were accepted to **ICLR 2025**.


# 📝 Publications 

<h3 class="sub-header animate-box" style="font-size: 12px; font-weight: 200; margin-bottom: 3px; padding-bottom: 3px">* indicates the equal contribution</h3>

## 2025

- <span class='paper-badge'>ICML 2025</span> **Provably Efficient Exploration in Inverse Constrained Reinforcement Learning** <span class='paper-asset'><a href="https://openreview.net/pdf?id=eLTPkGGHum">PDF</a></span><br>
  ***<u>Bo Yue</u>**, Jian Li, Guiliang Liu*<br>
  *International Conference on Machine Learning*, 2025 (CCF-A)<br>

- <span class='paper-badge'>ICLR 2025</span> **Understanding Constraint Inference in Safety-Critical Inverse Reinforcement Learning** <span class='paper-asset'><a href="https://openreview.net/pdf?id=B2RXwASSpy">PDF</a></span> <span class='paper-asset'><a href="https://github.com/Bobyue0118/Constraint-Inference-in-Safe-IRL">Code</a></span> [![](https://img.shields.io/github/stars/Bobyue0118/Constraint-Inference-in-Safe-IRL?style=social&label=Stars)](https://github.com/Bobyue0118/Constraint-Inference-in-Safe-IRL)<br>
  ***<u>Bo Yue</u>**, Shufan Wang, Ashish Gaurav, Jian Li, Pascal Poupart, Guiliang Liu*<br>
  *International Conference on Learning Representations*, 2025 (Tsinghua-A)<br>

- <span class='paper-badge'>ICLR 2025</span> **A Distributional Approach to Uncertainty-Aware Preference Alignment Using Offline Demonstrations** <span class='paper-asset'><a href="https://openreview.net/pdf?id=RKOAU5ti1y">PDF</a></span> <span class='paper-asset'><a href="https://github.com/Jasonxu1225/Uncertainty-aware-Preference-based-Reinforcement-Learning">Code</a></span> [![](https://img.shields.io/github/stars/Jasonxu1225/Uncertainty-aware-Preference-based-Reinforcement-Learning?style=social&label=Stars)](https://github.com/Jasonxu1225/Uncertainty-aware-Preference-based-Reinforcement-Learning)<br>
  *Sheng Xu, **<u>Bo Yue</u>**, Hongyuan Zha, Guiliang Liu*<br>
  *International Conference on Learning Representations*, 2025 (Tsinghua-A)<br>

- <span class='paper-badge'>ICLR 2025</span> **Toward Exploratory Inverse Constraint Inference with Generative Diffusion Verifiers** <span class='paper-asset'><a href="https://openreview.net/pdf?id=0UvlnHgaii">PDF</a></span> <span class='paper-asset'><a href="https://github.com/ZhaoRunyi/ExICL">Code</a></span> [![](https://img.shields.io/github/stars/ZhaoRunyi/ExICL?style=social&label=Stars)](https://github.com/ZhaoRunyi/ExICL) <br>
  *Runyi Zhao\*, Sheng Xu\*, **<u>Bo Yue</u>**, Guiliang Liu*<br>
  *International Conference on Learning Representations*, 2025 (Tsinghua-A)<br>

## 2023

- <span class='paper-badge'>Physica Scripta</span> **Quantum Approximate Optimization Algorithm in Non-Markovian Quantum Systems** <span class='paper-asset'><a href="https://iopscience.iop.org/article/10.1088/1402-4896/acf6e8/pdf">PDF</a></span><br>
  ***<u>Bo Yue</u>**, Shibei Xue, Yu Pan, Min Jiang*<br>
  *Physica Scripta, 98, 105104*, 2023 (JCR-Q2)<br>

- <span class='paper-badge'>CCC 2023</span> **Accelerated Simulation of Master Equation for Open Quantum Systems** <span class='paper-asset'><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10240232">PDF</a></span><br> 
  ***<u>Bo Yue</u>**, Yanfang Wang, Shibei Xue*<br>
  *Chinese Control Conference, 6748-6753*, 2023 (CAA-A)<br>

- <span class='paper-badge'>CCC 2023</span> **Accelerated Simulation of Non-Markovian Quantum Systems Using Quantum Trajectory** <span class='paper-asset'><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10240942">PDF</a></span><br> 
  *Yanfang Wang, **<u>Bo Yue</u>**, Shibei Xue*<br>
  *Chinese Control Conference, 6754-6759*, 2023 (CAA-A)<br>

- <span class='paper-prebadge'>arXiv 2023</span> **Local to Global: A Distributed Quantum Approximate Optimization Algorithm for Pseudo-Boolean Optimization Problems** <span class='paper-asset'><a href="https://arxiv.org/pdf/2310.05062">PDF</a></span><br>
  ***<u>Bo Yue</u>**, Shibei Xue, Yu Pan, Min Jiang, Daoyi Dong*<br>


# 🚀 Projects
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Auto Charge</div><img src='images/project.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- **Research on EV Autonomous Charging with Monocular Camera**

  *Qilong Wu\*, **<u>Bo Yue</u>**\*, Xin Liu, Shibei Xue*

  *School Corporate Cooperation Project with [Star Charge](https://www.wbstar.com/)*, 2022.09-2023.12

  Demo: &nbsp; [[Real Car]](https://www.bilibili.com/video/BV1ax4y1C7n3/?spm_id_from=333.880.my_history.page.click&vd_source=8debf3b3fb5f9dca46569bbb6cfa839c) &nbsp; [[Lab Env]](https://www.bilibili.com/video/BV1aN4y187i4/?spm_id_from=autoNext&vd_source=8debf3b3fb5f9dca46569bbb6cfa839c) &nbsp; uploaded by Qilong Wu
  
</div> </div>


# 🏅 Honors and Awards
- *2023.11* &nbsp; COSCO Shipping Scholarship of Shanghai Jiao Tong University (PG)
- *2022 / 2023.11* &nbsp; Shanghai Jiao Tong University First-Class Graduate Academic Scholarship
- *2020.12* &nbsp; COSCO Shipping Scholarship of Shanghai Jiao Tong University (UG)
- *2018.09* &nbsp; The Second Prize of National Undergraduate Mathematical Contest in Modeling
- *2017* / *2018* / *2019.12* &nbsp; Shanghai Jiao Tong University Zhiyuan Honors Program Scholarship


# 📖 Educations
- *2024.09 - (now)* &nbsp; The Chinese University of Hong Kong, Shenzhen, PhD in Computer Science, Advisor: Prof. [Guiliang Liu](https://guiliang.me/)
- *2021.09 - 2024.03* &nbsp; Shanghai Jiao Tong University, M.Eng. in Automation (Recommended for Postgraduate Studies), Advisor: Prof. [Shibei Xue](https://automation.sjtu.edu.cn/SXue)
- *2017.09 - 2021.06* &nbsp; Shanghai Jiao Tong University, B.Eng. in Automation (AI Direction)

<!-- 
# 💻 Internships
- *2023.10 - 2024.08* &nbsp; The Chinese University of Hong Kong, Shenzhen, Advisor: Prof. [Guiliang Liu](https://guiliang.me/)
-->

# 👨‍🏫 Teaching
- DDA2001 Introduction to Data Science: Teaching Assistant, Spring 2025


# 🔍 Service
- Conference Reviewer: ICLR 2025


<div id="globe-container">
<style>
  #globe-container {
    width: 150px; /* Set your desired width */
    height: 150px; /* Set your desired height */
  }
</style>
<!--
<script type="text/javascript" src="//rf.revolvermaps.com/0/0/6.js?i=59jot99u3ob&amp;m=8&amp;c=ff0000&amp;cr1=ffffff&amp;f=arial&amp;l=0&amp;rs=100&amp;as=10" async="async"></script>
</div>
<script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=2AEQhvsEmF_xjX8-SslDxxPtIHLUZqZ2DPUGECWWRs4"></script>
  -->
<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=250&t=tt&d=2AEQhvsEmF_xjX8-SslDxxPtIHLUZqZ2DPUGECWWRs4&co=2d78ad&ct=ffffff&cmo=3acc3a&cmn=ff5353'></script>
