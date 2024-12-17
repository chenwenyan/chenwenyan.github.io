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

Greetings! I am a forth-year PhD student in the Computer Science at Cloud and Distributed Systems (CDS) Lab at University of Macau (2021-Present), supervised by [Prof. Huanle Xu (徐欢乐)](https://www.fst.um.edu.mo/people/huanlexu) and [Prof. Kejiang Ye (叶可江)](https://people.ucas.edu.cn/~kejiang?language=en). My reseach interests focus on cloud computing, GPU virtualization, systems for ML.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2024.07*: &nbsp;🎉🎉 Mudi is accepted by EuroSys 2025.  
- *2024.06*: &nbsp;🎉🎉 SMIless is accepted by SC 2024. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EuroSys 2025</div><img src='images/mudi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multiplexing Dynamic Deep Learning Workloads with SLO-awareness in GPU Clusters](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Wenyan Chen**, Chengzhi Lu, Huanle Xu, Kejiang Ye, Chengzhong Xu.

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- <div class="badge">SC 2024</div> [SMIless: Serving DAG-based Inference with Dynamic Invocations under Serverless Computing](https://github.com), Chengzhi Lu, Huanle Xu, Yudan Li, **Wenyan Chen**, Kejiang Ye, Chengzhong Xu. 

- [Interference-aware Multiplexing for Deep Learning in GPU Clusters: A Middleware Approach](https://dl.acm.org/doi/pdf/10.1145/3581784.3607060), Wenyan Chen, Zizhao Mo, Huanle Xu, Kejiang Ye, Chengzhong Xu. **SC 2023**. [[Code]](https://github.com/buzy-coder/IADeep) [[Slides]](http://chenwenyan.github.io/files/IADeep-slides.pdf) 

- [RPTCN: Resource prediction for high-dynamic workloads in clouds based on deep learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9556034), **Wenyan Chen**, Chengzhi Lu, Kejiang Ye, Yang Wang, Chengzhong Xu. **CLUSTER 2021**

- [HySync: Hybrid federated learning with effective synchronization](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9407951), Guomei Shi, Li Li, Jun Wang, **Wenyan Chen**, Kejiang Ye, ChengZhong Xu. **HPCC 2020**

- [ADGS: anomaly detection and localization based on graph similarity in container-based clouds](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8975844) Chengzhi Lu, Kejiang Ye, **Wenyan Chen**, Chengzhong Xu. **ICPADS 2020**

- [Co-locating online workload and offline workload in the cloud: An interference analysis](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8855680) **Wenyan Chen**, Kejiang Ye, Chengzhong Xu. **HPCC 2019**

- [How does the workload look like in production cloud? analysis and clustering of workloads on alibaba cluster trace](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8644579) **Wenyan Chen**, Kejiang Ye, Yang Wang, Guoyao Xu, Chengzhong Xu. **ICPADS 2018**



# 🎖 Honors and Awards
- *2019.06* 东北师范大学优秀毕业生
- *2015.04* 郑州大学ACM程序设计大赛一等奖

# 📖 Educations
- *2021.08 - now*, PhD, Computer Science, University of Macau.
- *2016.09 - 2019.07*, Master. Software Engineering, Northeast Normal University.
- *2012.09 - 2016.06*, BS, Software Engineering, Zhengzhou University. 

# 💬 Talks
- *2023.12*, ChinaSys 2023 Fall，Interference-aware Multiplexing for Deep Learning in GPU Clusters: A Middleware Approach. *Lanzhou, China*  
- *2023.11*, SC 2023，Interference-aware Multiplexing for Deep Learning in GPU Clusters: A Middleware Approach. *Denver, USA* 

# 🧑‍🎨 Teaching
- *2021 Winter*, Teaching Assistant. Human-Computer Interaction

# 💻 Reseach Activity
- *TCE 2024*, Reviwer
- *HDIS 2023*, Web Chair