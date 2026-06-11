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

Hello there! I'm Guodong Du, a PhD student at [The Hong Kong Polytechnic University (PolyU)](https://www.polyu.edu.hk/). Before that, I was a research assistant at the [Knowledge and Language Computing Lab](http://www.li-jing.com/team.html) @ Harbin Institute of Technology (Shenzhen), working with Prof. Jing Li. Earlier, I was a master's student and research intern at the [Learning and Vision Lab](http://lv-nus.org) @ National University of Singapore, advised by Prof. [Xinchao Wang](https://sites.google.com/site/sitexinchaowang/) and [Jiashi Feng](https://sites.google.com/site/jshfeng/), and interned at [Huawei Noah's Ark Lab](https://www.noahlab.com.hk/#/home).

My research centers on **large language models** — **model merging & knowledge fusion**, **post-training & alignment** (RLHF / multi-objective), and **training & inference efficiency** (compression, pruning, quantization). More recently I also work on multimodal LLMs and embodied intelligence (Vision-Language-Action).

# 🔥 News
 <span style="color: blue;">Good News</span>      <span style="color: gray;">Bad News</span>.



- *2026.04*: &nbsp;🎉 <span style="color: blue;">One co-corresponding and one co-first author paper are accepted by ACL 2026 Findings.</span> 
- *2026.01*: &nbsp;🎉 <span style="color: blue;">One first author and one co-first author paper are accepted by ICLR 2026.</span> 
- *2025.08*: &nbsp;🎉 <span style="color: blue;">One co-corresponding paper is accepted by EMNLP 2025 main.</span> 
- *2025.05*: &nbsp;🎉 <span style="color: blue;">One first author and one co-first author paper are accepted by ACL 2025 main.</span> 
- *2024.09*: &nbsp;🎉 <span style="color: blue;">One first author paper is accepted by NeurIPS 2024.</span> 
- *2024.05*: &nbsp;🎉 <span style="color: blue;">One first author paper is accepted by ACL 2024 Findings.</span> 


# 📝 Recent Projects 

- Knowledge Fusion: A Comprehensive Survey. [Github Repo](https://github.com/duguodong7/Awesome-Knowledge-Fusion)
- FuseVLA-benchmark — a systematic benchmark for VLA model merging.
- RoboMemPlan — memory-aware subtask planning for long-horizon embodied tasks.


# 📝 Publications 

<small>( <b>bold</b>: me &nbsp;·&nbsp; \*: co-first author &nbsp;·&nbsp; †: corresponding author )</small>

### Model Merging & Knowledge Fusion

- `ICLR 2026` [**Knowledge Fusion of Large Language Models Via Modular SkillPacks**](https://arxiv.org/abs/2505.18502) <br>
  **Guodong Du**, Xuanning Zhou, Junlin Lee, Zhuo Li, Wanyu Lin, Jing Li† <br>
  [paper](https://arxiv.org/abs/2505.18502) | [code](https://github.com/duguodong7/graftllm)

- `NeurIPS 2024` [**Parameter Competition Balancing for Model Merging**](https://arxiv.org/pdf/2410.02396) <br>
  **Guodong Du**, Junlin Lee, Jing Li†, Hanting Liu, Runhua Jiang, Shuyang Yu, Yifei Guo, Sim Kuan Goh, Ho-Kin Tang†, Min Zhang <br>
  [paper](https://arxiv.org/pdf/2410.02396) | [code](https://github.com/duguodong7/pcb-merging)

- `EMNLP 2025 main` [**To See a World in a Spark of Neuron: Disentangling Multi-task Interference for Training-free Model Merging**](https://arxiv.org/abs/2503.05320) <br>
  Zitao Fang, **Guodong Du**†, Jing Li, Ho-Kin Tang, Sim Kuan Goh† <br>
  [paper](https://arxiv.org/abs/2503.05320) | [project](https://zzzitaofang.github.io/projects/NeuroMerging/)

- `ACL 2025 main` [**Neural Parameter Search for Slimmer Fine-Tuned Models and Better Transfer**](https://arxiv.org/abs/2505.18713) <br>
  **Guodong Du**, Zitao Fang, Junlin Lee, Runhua Jiang, Jing Li† <br>
  [paper](https://arxiv.org/abs/2505.18713) | [code](https://github.com/duguodong7/NPS-Pruning)

- `ACL 2024 Findings` [**Knowledge Fusion By Evolving Weights of Language Models**](https://arxiv.org/pdf/2406.12208) <br>
  **Guodong Du**, Jing Li, Hanting Liu, Runhua Jiang, Shuyang Yu, Yifei Guo, Sim Kuan Goh†, Ho-Kin Tang† <br>
  [paper](https://arxiv.org/pdf/2406.12208) | [code](https://github.com/duguodong7/model-evolution)

- `ACL 2026 Findings` [**Skill Weaving: Efficient LLM Improvement via Modular Skillpacks**](https://arxiv.org/abs/2605.22205) <br>
  Zhuo Li\*, **Guodong Du**\*, Zesheng Shi, Weiyang Guo, Jing Li† <br>
  [paper](https://arxiv.org/abs/2605.22205)

- `Preprint` [**DiDi-Merging: Dynamic Model Merging Made Slim**](https://arxiv.org/abs/2605.18904) <br>
  **Guodong Du**, Wanyu Lin† <br>
  [paper](https://arxiv.org/abs/2605.18904)

### LLM Alignment & Post-training

- `ICLR 2026` [**Multi-objective Large Language Model Alignment with Hierarchical Experts (HoE)**](https://arxiv.org/abs/2505.20925) <br>
  Zhuo Li, **Guodong Du**\*, Wenya Wang, Min Zhang, Jing Li† <br>
  [paper](https://arxiv.org/abs/2505.20925)

### Efficient & Compressed LLMs

- `ACL 2026 Findings` [**D-QReLO: Training- and Data-Free Delta Compression for LLMs via Quantization and Residual Low-Rank Approximation**](https://arxiv.org/abs/2604.16940) <br>
  Junlin Li, **Guodong Du**†, Ngai Wong, Min Zhang, Jing Li, Xuelong Li† <br>
  [paper](https://arxiv.org/abs/2604.16940)

### Multimodal LLMs & Embodied Intelligence

- `ACL 2025 main` [**Multi-Modality Expansion and Retention for LLMs through Parameter Merging and Decoupling**](https://arxiv.org/abs/2505.17110) <br>
  Junlin Lee, **Guodong Du**\*, Wenya Wang, Jing Li† <br>
  [paper](https://arxiv.org/abs/2505.17110)

### Earlier Work (Low-level Vision & Evolutionary Methods)

- `IEEE SMC 2024` [Impacts of Darwinian Evolution on Pre-trained Deep Neural Networks](https://arxiv.org/pdf/2408.05563), **Guodong Du**, et al.
- `IEEE Cyber 2024` [MOESR: Multi-Objective Evolutionary Algorithm for Image Super-Resolution](https://duguodong7.github.io/), **Guodong Du**, et al. 
- `CVPR 2021 Workshop` [NTIRE 2021 challenge on video super-resolution](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/papers/Son_NTIRE_2021_Challenge_on_Video_Super-Resolution_CVPRW_2021_paper.pdf), 3rd Place Award.
- `ArXiv 2020` [End-to-end Rain Streak Removal with RAW Images](https://arxiv.org/abs/2312.13304), **Guodong Du**, et al. 


# 🎖 Honors and Awards
- *2021.10* 3rd Place Award in NTIRE 2021 Challenge on Video Super-resolution, Track I. (New Trends in Image Restoration and Enhancement Workshop, CVPR2021)
- *2017.09* National scholarship
- *2016.05* Honorable Award in MCM (The Mathematical Contest in Modeling)
- *2016.05* National Encouragement scholarship
- *2015.05* National Encouragement scholarship

# 📖 Educations
- *2025.08 - 2028.06 (expected)*, Ph.D. student, The Hong Kong Polytechnic University (PolyU)
- *2018.08 - 2019.05*, M.S., National University of Singapore (NUS) 
- *2016.07 - 2016.12*, Visiting, City University of Hong Kong (CityU) (Non-degree Undergraduate Exchange)
- *2014.08 - 2018.06*, B.S., University of Electronic Science and Technology of China (UESTC)

# 💻 Internships
- *2024.03 - 2024.09*, [Knowledge and Language Computing Lab](http://www.li-jing.com/team.html), Shenzhen, China.
- *2023.03 - 2024.09*, [Harbin Institute of Technology (Shenzhen)](http://en.hitsz.edu.cn/), China.
- *2019.09 - 2021.09*, [Learning and Vision Lab](http://lv-nus.org), Singapore.
- *2020.08 - 2021.04*, [Huawei Noah's Ark Lab](https://www.noahlab.com.hk/#/home), Shenzhen, China.
- *2019.01 - 2019.09*, [Biomind](https://www.biomind.cn), Singapore.
- *2018.01 - 2018.04*, YoueData, Chengdu, China
