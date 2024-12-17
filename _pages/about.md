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

Greetings! I am a forth-year PhD student in the Computer Science at Cloud and Distributed Systems (CDS) Lab at University of Macau (2021-Present), supervised by <span style="text-decoration: underline;">[Prof. Huanle Xu (徐欢乐)](https://www.fst.um.edu.mo/people/huanlexu)</span> and <span style="text-decoration: underline;">[Prof. Kejiang Ye (叶可江)](https://people.ucas.edu.cn/~kejiang?language=en)</span>. My research interests focus on cloud computing, GPU virtualization, systems for ML. <a href='https://scholar.google.com/citations?user=WKFOF1cAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.07*: &nbsp;🎉🎉 Mudi is accepted by EuroSys 2025.  

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">EuroSys 2025</div><img src='images/mudi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multiplexing Dynamic Deep Learning Workloads with SLO-awareness in GPU Clusters](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Wenyan Chen**, Chengzhi Lu, Huanle Xu, Kejiang Ye, Chengzhong Xu.

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

- <span class="conf_title_badge">EuroSys 2025</span> <a href="pdfs/mudi.pdf">Multiplexing Dynamic Deep Learning Workloads with SLO-awareness in GPU Clusters</a>, **Wenyan Chen**, Chengzhi Lu, Huanle Xu, Kejiang Ye, Chengzhong Xu. 

- <span class="conf_title_badge">SC 2024</span> [SMIless: Serving DAG-based Inference with Dynamic Invocations under Serverless Computing](https://dl.acm.org/doi/pdf/10.1109/SC41406.2024.00044), Chengzhi Lu, Huanle Xu, Yudan Li, **Wenyan Chen**, Kejiang Ye, Chengzhong Xu. <span class='show_paper_citations' data='WKFOF1cAAAAJ:ufrVoPGSRksC'></span>

- <span class="conf_title_badge">SC 2023</span> [Interference-aware Multiplexing for Deep Learning in GPU Clusters: A Middleware Approach](https://dl.acm.org/doi/pdf/10.1145/3581784.3607060), **Wenyan Chen**, Zizhao Mo, Huanle Xu, Kejiang Ye, Chengzhong Xu. [[Code]](https://github.com/buzy-coder/IADeep) <a href="pdfs/IADeep-slides.pdf">[Slides]</a> <span class='show_paper_citations' data='WKFOF1cAAAAJ:YsMSGLbcyi4C'></span> 

- <span class="conf_title_badge">CLUSTER 2021</span> [RPTCN: Resource prediction for high-dynamic workloads in clouds based on deep learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9556034), **Wenyan Chen**, Chengzhi Lu, Kejiang Ye, Yang Wang, Chengzhong Xu. <span class='show_paper_citations' data='WKFOF1cAAAAJ:Tyk-4Ss8FVUC'></span> 

- <span class="conf_title_badge">HPCC 2020</span> [HySync: Hybrid federated learning with effective synchronization](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9407951), Guomei Shi, Li Li, Jun Wang, **Wenyan Chen**, Kejiang Ye, ChengZhong Xu. <span class='show_paper_citations' data='WKFOF1cAAAAJ:zYLM7Y9cAGgC'></span> 

- <span class="conf_title_badge">ICPADS 2020</span> [ADGS: anomaly detection and localization based on graph similarity in container-based clouds](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8975844) Chengzhi Lu, Kejiang Ye, **Wenyan Chen**, Chengzhong Xu. <span class='show_paper_citations' data='WKFOF1cAAAAJ:d1gkVwhDpl0C'></span> 

- <span class="conf_title_badge">HPCC 2019</span> [Co-locating online workload and offline workload in the cloud: An interference analysis](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8855680) **Wenyan Chen**, Kejiang Ye, Chengzhong Xu. <span class='show_paper_citations' data='WKFOF1cAAAAJ:u-x6o8ySG0sC'></span> 

- <span class="conf_title_badge">ICPADS 2018</span> [How does the workload look like in production cloud? analysis and clustering of workloads on alibaba cluster trace](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8644579) **Wenyan Chen**, Kejiang Ye, Yang Wang, Guoyao Xu, Chengzhong Xu. <span class='show_paper_citations' data='WKFOF1cAAAAJ:u5HHmVD_uO8CC'></span>


# 🎖 Honors and Awards
- *2019.06*, Outstanding Graduate of Northeast Normal University
- *2015.04*, First Prize of ACM Programming Contest in Zhengzhou University 

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
- *TCE 2024*, Reviewer
- *HDIS 2023*, Web Chair