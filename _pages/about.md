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

Hi, I am a Year 4 CS Ph.D. candidate at Beihang University, supervised by [Prof. Hailong Yang](https://thomas-yang.github.io/) and work as a member of [Hipo Group](https://github.com/buaa-hipo). I received my bachelor's degree of computer science and engineering at Beihang University in 2022. 

My research interests include machine learning system optimizations and high performance computing. Specifically, I focus on accelerating deep learning model training and inference, as well as leveraging AI techniques to optimize traditional HPC workloads, such as stencil computations. I am looking forward to collaborations and research internship opportunities. If you are interested in my work, please feel free to reach out.



# 🔥 News
- *2025.11*: &nbsp;🎉🎉ElasGNN is accepted to PPoPP‘26. 
- *2025.10*: &nbsp;🎉🎉 The xLLM inference engine, to which I contributed, has released 
its technical report.
- *2025.06*: &nbsp;🎉🎉 Smurfs is accepted to SC’25. 
- *2025.06*: &nbsp;🎉🎉 ESC is accepted to ICPP’25. 
- *2025.03*: &nbsp;🎉🎉 Plasticine is accepted to ICS’25.
 - *2024.03*: &nbsp;🎉🎉 AtRec is accepted to TPDS.

# 📝 Publications 

[ElasGNN: An Elastic Training Framework for Distributed GNN Training.](https://dl.acm.org/doi/10.1145/3774934.3786440)
**Siqi Wang**, Hailong Yang, Pengbo Wang, Hongliang Cao, Yufan Xu, Xuezhu Wang, et al.
PPoPP 2026

[Towards Efficient LLM Inference via Collective and Adaptive Speculative Decoding.](https://dl.acm.org/doi/10.1145/3712285.3759834)
**Siqi Wang**, Hailong Yang, Xuezhu Wang, Tongxuan Liu, Pengbo Wang, Yufan Xu, et al.
SC 2025

[Accelerating Complex Stencil Computations with Adaptive Fusion Strategy.](https://dl.acm.org/doi/10.1145/3721145.3725768)
**Siqi Wang**, Hailong Yang, Pengbo Wang, Shaokang Du, Yufan Xu, Qingxiao Sun, et al.
ICS 2025

[ESC: Effective Submanifold Convolution using Tensor Cores.](https://dl.acm.org/doi/10.1145/3754598.3754633)
Xuezhu Wang, Hailong Yang, Xin You, Yufan Xu, Xiaoyan Liu, **Siqi Wang**, et al.
ICPP 2025


[xLLM Technical Report.](https://arxiv.org/abs/2510.14686)
Tongxuan Liu, Tao Peng, Peijun Yang, Xiaoyang Zhao, Xiusheng Lu, Weizhe Huang, Zirui Liu, Xiaoyu Chen, Zhiwei Liang, Jun Xiong, Donghe Jin, Minchao Zhang, Jinrong Guo, Yingxu Deng, Xu Zhang, Xianzhe Dong, **Siqi Wang**, et al.
Arxiv 2025

[RLHFSpec: Breaking the Efficiency Bottleneck in RLHF Training via Adaptive Drafting](https://arxiv.org/abs/2512.04752)
**Siqi Wang**, Hailong Yang, Junjie Zhu, Xuezhu Wang, Yufan Xu, Depei Qian.
Arxiv 2025



[AtRec: Accelerating recommendation model training on CPUs.](https://ieeexplore.ieee.org/document/10478579/)
**Siqi Wang**, Tianyu Feng, Hailong Yang, Xin You, Bangduo Chen, Tongxuan Liu, et al.
TPDS 2024

[Exploiting Structured Feature and Runtime Isolation for High-Performant Recommendation Serving.](https://ieeexplore.ieee.org/document/10654386/)
Xin You, Hailong Yang, **Siqi Wang**, Tao Peng, Chen Ding, Xinyuan Li, et al.
TC 2024




# 💻 Industry Experience
- *2025 - present*, xLLM Large Language Model Inference Engine — JD.com.
- *2025, Agentic Workflow Optimization — SenseTime.
- *2024 - 2025, Adaptive Speculative Decoding for LLM Inference — SenseTime.
- *2023 - 2024, Recommendation Model Training Acceleration — Alibaba.

# 🎖 Honors and Awards
- Global runner-up, Intel "Innovation Master Cup" Global AI Geek Challenge — DeepRec CTR Model Performance Optimization.