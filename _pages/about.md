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

Hello there! I'm Guodong Du, currently a research assistant at [Knowledge and Language Computing Lab](http://www.li-jing.com/team.html) @Harbin Institute of Technology (Shenzhen).
Prior to joining HITSZ, I was a research intern and master student in [Learning and Vision Lab](http://lv-nus.org) @National University of Singapore, advised by Professor [Xinchao Wang](https://sites.google.com/site/sitexinchaowang/) and [Jiashi Feng](https://sites.google.com/site/jshfeng/).  Besides, I had been working as an intern in the area of low level computer vision, mentored by [Xueyi Zou](https://scholar.google.com/citations?user=0ua28KoAAAAJ&hl=en), in [Huawei Noah's Ark Lab](https://www.noahlab.com.hk/#/home), Shenzhen, China.

My research interest includes knowledge transfer, fusion and compression, multimodal, heuristic algorithms, spiking neural networks and low level computer vision.

# 🔥 News
 <span style="color: blue;">Good News</span>      <span style="color: gray;">Bad News</span>.

- *2024.09*: &nbsp;One co-first author paper is submitted to ICLR 2025.

- *2024.09*: &nbsp;🎉🎉🎉 <span style="color: blue;">One first author papers is accepted by NeurIPS 2024.</span> Thanks to all my collaborators!.
- *2024.08*: &nbsp;One first author paper is submitted to AAAI 2025.
- *2024.07*: &nbsp;🎉🎉🎉 <span style="color: blue;">One first author papers is accepted by IEEE SMC 2024.</span> Thanks to all my collaborators!.
- *2024.05*: &nbsp;🎉🎉🎉 <span style="color: blue;">One first author paper is accepted by ACL 2024 Findings.</span> Thanks to all my collaborators!.
- *2024.03*: &nbsp;🎉🎉🎉 <span style="color: blue;">One co-first author papers is accepted by IJCNN 2024.</span> Thanks to all my collaborators!.
- *2023.12*: &nbsp; <span style="color: gray;">Two first author papers are rejected by ICLR 2024.</span> 

# 📝 Recent Projects 

- Knowledge Grafting of Large Language Models. [Poster](https://duguodong7.github.io/files/knowledge_grafting2.png)
- Knowledge Fusion: A Comprehensive Survey. [Github Repo](https://github.com/duguodong7/Awesome-Knowledge-Fusion), <a href="https://github.com/duguodong7/Awesome-Knowledge-Fusion"><img src="https://img.shields.io/github/stars/duguodong7/Awesome-Knowledge-Fusion?style=social&label=Stars"></a>
- Multi-Modality LLMs Knowledge Fusion And Decoupling. [[PDF]](https://duguodong7.github.io/files/MMER_w_supp.pdf), [[Poster]](https://duguodong7.github.io/files/mmer2.png), submitted to ICLR 2025.
- Neural Parameter Search For Improved Knowledge Transfer, Fusion and Compression. [[PDF]](https://duguodong7.github.io/files/NPS_For_Knowledge_Transfer__Fusion_and_Compression_w_supp.pdf), [[Poster]](https://duguodong7.github.io/files/NPS_pruning.png), submitted to AAAI 2025.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/pcb_merging_00.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Parameter Competition Balancing for Model Merging](https://arxiv.org/pdf/2410.02396)

**Guodong Du**, Junlin Lee, Jing Li, Hanting Liu, Runhua Jiang, Shuyang Yu, Yifei Guo, Sim Kuan Goh, Ho-Kin Tang, Min Zhang 

[arXiv](https://arxiv.org/pdf/2410.02396)
|
<a href="https://github.com/duguodong7/pcb-merging"><img src="https://img.shields.io/github/stars/duguodong7/pcb-merging?style=social&label=Stars"></a>
|
[code](https://github.com/duguodong7/pcb-merging)
|
[poster](https://arxiv.org/pdf/2410.02396)
- We re-examine existing model merging methods, emphasizing the critical importance of parameter competition awareness, and introduce PCB-Merging, which effectively adjusts parameter coefficients. 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/evolver_00.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Knowledge Fusion By Evolving Weights of Language Models](https://arxiv.org/pdf/2406.12208)

**Guodong Du**, Jing Li, Hanting Liu, Runhua Jiang, Shuyang Yu, Yifei Guo, Sim Kuan Goh, Ho-Kin Tang 

[arXiv](https://arxiv.org/pdf/2406.12208)
|
<a href="https://github.com/duguodong7/model-evolution"><img src="https://img.shields.io/github/stars/duguodong7/model-evolution?style=social&label=Stars"></a>
|
[code](https://github.com/duguodong7/model-evolution)
|
[poster](https://arxiv.org/pdf/2406.12208)
- Model Evolution is the first approach to evolve neural parameters using Differential Evolutionary Algorithms. We introduce a novel knowledge fusion method by evolving weights of  (large)  language models.

- [Impacts of Darwinian Evolution on Pre-trained Deep Neural Networks](https://arxiv.org/pdf/2408.05563), **Guodong Du**, et al. **IEEE SMC24**
- [CADE: Cosine Annealing Differential Evolution for Spiking Neural Network](https://arxiv.org/pdf/2406.02349), Runhua Jiang\*, **Guodong Du**\*, et al. **IJCNN24**
- [Evolutionary Neural Architecture Search for 3D Point Cloud Analysis](https://arxiv.org/pdf/2408.05556), Yisheng Yang, **Guodong Du**, et al. **IEEE SMC24**
- [MOESR: Multi-Objective Evolutionary Algorithm for Image Super-Resolution](https://duguodong7.github.io/), **Guodong Du**, et al. **IEEE Cyber**
- [NTIRE 2021 challenge on video super-resolution](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/papers/Son_NTIRE_2021_Challenge_on_Video_Super-Resolution_CVPRW_2021_paper.pdf), 3rd Place Award, **CVPR2021 Workshop**
- [End-to-end Rain Streak Removal with RAW Images](https://arxiv.org/abs/2312.13304), **Guodong Du**, et al. **ArXiv20**
- [Learning generalizable and identity-discriminative representations for face anti-spoofing](https://arxiv.org/pdf/1901.05602) Xiaoguang Tu, **Guodong Du**, et al. **ACM Transactions on Intelligent Systems and Technology (TIST 2020)**
&nbsp; &nbsp; ( *: Co-first Author )

# 🎖 Honors and Awards
- *2021.10* 3rd Place Award in NTIRE 2021 Challenge on Video Super-resolution, Track I. (New Trends in Image Restoration and Enhacement Workshop, CVPR2021)
- *2017.09* National Encouragement scholarship
- *2016.05* Honorable Award in MCM (The Mathematical Contest in Modeling)
- *2016.05* National Encouragement scholarship
- *2015.05* National scholarship

# 📖 Educations
- *2019.09 - 2021.05*, Part-time PhD student, National University of Singapore (NUS)
- *2018.08 - 2019.05*, M.S., National University of Singapore (NUS) 
- *2016.07 - 2016.12*, Visiting. City University of Hong kong (CityU) (Non-degree Undergraduate Exchange)
- *2014.08 - 2018.06*, B.S., University of Electronic Science and Technology of China (UESTC)

# 💻 Internships
- *2024.03 - 2024.09*, [Knowledge and Language Computing Lab](http://www.li-jing.com/team.html), Shenzhen, China.
- *2023.03 - 2024.09*, [Harbin Institute of Technology (Shenzhen)](http://en.hitsz.edu.cn/), China.
- *2019.09 - 2021.09*, [Learning and Vision Lab](http://lv-nus.org), Singapre.
- *2020.08 - 2021.04*, [Huawei Noah's Ark Lab](https://www.noahlab.com.hk/#/home), Shenzhen, China.
- *2019.01 - 2019.09*, [Biomind](https://www.biomind.cn), Singapore.
- *2018.01 - 2018.04*, YoueData, Chengdu, China

