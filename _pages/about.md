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

<span style="font-size: 1.3em; font-family: 'Merriweather', serif;">I am a Senior Research Fellow at the Institute of Operations Research and Analytics (IORA), National University of Singapore. I am fortunately advised by [Prof. Chung-Piaw Teo](https://www.teochungpiaw.com/) and [Prof. Mabel C.Chou](https://iora.nus.edu.sg/people-p/mabel-chou/). I also work closely with [Prof. Zhou Xu](https://sites.google.com/view/xuzhou) and [Prof. Zhenzhen Yan](https://sites.google.com/view/zhenzhenyan/home). I hold a Ph.D. in Management Science and Engineering from the School of Business, Sun Yat-sen University, Guangzhou, and a B.Eng. in Intelligent Transportation Systems from the School of Engineering, Sun Yat-sen University.</span>

<span style="font-size: 1.3em; font-family: 'Merriweather', serif;">My current research interest involves using data-driven optimization, empirical analysis and deep learning tools to tackle challenging logistics and supply chain problems in close collaboration with industry. This line of research has led to the development of the Joint Prediction and Optimization (JPO) system for demand forecasting and inventory control, with beta v1.0 launched on August 29, 2024, for internal use at NUS and in undergraduate teaching. Additionally, I have developed the [LogXHub system](https://appbyjinjiahuang.shinyapps.io/Demo1_DynamicPlanningSystemforCrossDockingOperations_Beta_v9/) to optimize buffer inventory and enhance dynamic cross-docking operations at hubs.</span>


# 🔥 News
- *2024.09*: &nbsp; <b>I am on the 2024-2025 academic job market.</b>

# 📝 Publications 
## <span style="color: blue;">Strategic Network Design: A Little Flexibility Is All You Need</span>
 - **Jinjia Huang**, Mabel C. Chou,  Chung-Piaw Teo, [Bike-repositioning using volunteers: crowd sourcing with choice restriction](https://ojs.aaai.org/index.php/AAAI/article/view/17407), <b><em>In Proceedings of the AAAI Conference on Artificial Intelligence</em></b>, 35(13), 11844-11852, 2021.
<div class='paper-box'><div class='paper-box-image' style="margin-top: -3.5em; padding-top: 0; margin-bottom: 0"><div><div class="badge">AAAI 2021</div><img src='/images/F5_AAAI.jpg' alt="sym" width="100%" style="height:100%"></div></div>
<div class='paper-box-text' markdown="1" style="margin-top: -2.5em; padding-top: 0; margin-bottom: 0">
[**Research**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We study the use of registered volunteers to re-position empty bikes for riders in a bike sharing system.
- We solve a transshipment network design model to account for random route demand and construct a sparse structure that limits volunteer re-balancing to essential routes.
- This provide new insights into the performance of sparse structures in bike re-balancing, showing that concentrating flows reduces redundant moves significantly with minimal impact on demand satisfaction.
</div>
</div>  

 - **Jinjia Huang**, Zhenzhen Yan, Mabel C. Chou,  Chung-Piaw Teo, [The Paradox of Choice: Why Less Can Be More in Decentralized Resource Sharing System], <b><em>Submitting to Manufacturing & Service Operations Management soon</em></b>, 2024.
<div class='paper-box'><div class='paper-box-image' style="margin-top: -2.5em; padding-top: 0; margin-bottom: 0"><div><div class="badge">Research 2024</div><img src='/images/F0_WebAppDashBoard_Sep2024.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="margin-top: -1.5em; padding-top: 0; margin-bottom: 0">
[**Research**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We develop a novel network design model for repositioning operations, leveraging conic programming and distributionally robust optimization. 
- We provide arguably the first study on constructing sparse networks in decentralized deployment with choice behavior.
- We reveal a paradoxical phenomenon: sometimes, <em> less (choices) can be more (efficient)</em>. We provide new sights into the value of sparse structures.
</div>
</div> 

## <span style="color: blue;">Hub Operations: Robustness Boosts Efficiency</span>

 - **Jinjia Huang**, Chung-Piaw Teo, Fan Wang, Zhou Xu, [Buffer Times Between Scheduled Events in Resource Assignment Problem: A Conflict-Robust Perspective](https://iora.nus.edu.sg/wp-content/uploads/2023/06/ConflictRobustPaper_JinjiaHuang.pdf), <b><em>Manufacturing & Service Operations Management</em></b>, 25(6), 2268-2276, 2023.

<div class='paper-box'><div class='paper-box-image' style="margin-top: -3.5em; padding-top: 0; margin-bottom: 0"><div><div class="badge">M&SOM 2023</div><img src='/images/F1_ConflictRobust.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="margin-top: -2.5em; padding-top: 0; margin-bottom: 0">
[**Research**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We address the fundamental resource assignment problem faced by hub operators managing multiple services with scheduled starting and completion times, accounting for uncertain delays revealed over time.
- We derive a new insight that conflicts and crossings are equivalent under worst-case delay realization.
- This provides the first theoretical explanation, from the perspective of (distributionally) robust optimization for the good performance of the buffering approach in minimizing both crossings and conflicts in the
operations.
</div>
</div>  


## <span style="color: blue;">End-to-End Decision Making: Benefits of Data Pooling</span>

 - **Jinjia Huang**,  Mabel C. Chou, Chung-Piaw Teo,  Graph Neural Network: Forecasting and Replenishment Planning, <b><em>Submitting to Production and Operations Management soon</em></b>, 2024.

<div class='paper-box'><div class='paper-box-image' style="margin-top: -2.5em; padding-top: 0; margin-bottom: 0"><div><div class="badge">Research 2024</div><img src='/images/F6_JPO.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="margin-top: -2.5em; padding-top: 0; margin-bottom: 0">
[**Research & Project**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We explore the use of a class of Graph Neural Network (GNN) in modeling and exploiting the correlated demand patterns in multiple time series data. 
- We describe an application of GNN approach on a printer service management problem posed by an industry collaborator.
- This project led to the development of the Joint Prediction and Optimization (JPO) system for demand forecasting and inventory control. The JPO system beta v1.0 was launched on August 29, 2024, for
internal use at NUS and has been used in undergraduate course teaching exercises.
- We provide the novel insight that GNNs might benefit from the data pooling effect inherent to a statistical phenomenon.
</div>
</div>  



- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
