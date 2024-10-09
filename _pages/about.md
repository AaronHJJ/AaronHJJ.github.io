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

<span style="font-size: 1.3em; font-family: 'Merriweather', serif;"> Hi! I am a Senior Research Fellow at the Institute of Operations Research and Analytics (IORA), National University of Singapore (NUS). Trained initially at Sun Yat-sen University, and later refined at Department of Analytics and Operations (DAO) and IORA at NUS, I am fortunately advised by [Prof. Chung-Piaw Teo](https://www.teochungpiaw.com/) and [Prof. Mabel C.Chou](https://iora.nus.edu.sg/people-p/mabel-chou/). I also work closely with [Prof. Fan Wang](https://bus.sysu.edu.cn/en/teacher/WangFan), [Prof. Zhou Xu](https://sites.google.com/view/xuzhou) and [Prof. Zhenzhen Yan](https://sites.google.com/view/zhenzhenyan/home). </span>

<span style="font-size: 1.3em; font-family: 'Merriweather', serif;">My current research interest involves using data-driven optimization, empirical analysis and deep learning tools to tackle challenging logistics and supply chain problems in close collaboration with industry. This line of research has led to the development of the Joint Prediction and Optimization (JPO) system for demand forecasting and inventory control, with beta v1.0 launched on August 29, 2024, for internal use at NUS and in undergraduate teaching. Additionally, I have developed the [LogXHub system](https://appbyjinjiahuang.shinyapps.io/Demo1_DynamicPlanningSystemforCrossDockingOperations_Beta_v9/) to optimize buffer inventory and enhance dynamic cross-docking operations at hubs.</span>

<span class='anchor' id='-news'></span>
#  News
- *2024.09*: &nbsp; <b>I am on the 2024-2025 academic job market.</b>

<span class='anchor' id='-publications'></span>
#  Publications & Revisions
 - **Jinjia Huang**, Mabel C. Chou,  Chung-Piaw Teo, [Bike-repositioning Using Volunteers: Crowd Sourcing with Choice Restriction](https://ojs.aaai.org/index.php/AAAI/article/view/17407), <b><em>In Proceedings of the AAAI Conference on Artificial Intelligence</em></b>, 35(13), 11844-11852, 2021.
 - **Jinjia Huang**, Chung-Piaw Teo, Fan Wang, Zhou Xu, [Buffer Times Between Scheduled Events in Resource Assignment Problem: A Conflict-Robust Perspective](https://iora.nus.edu.sg/wp-content/uploads/2023/06/ConflictRobustPaper_JinjiaHuang.pdf), <b><em>Manufacturing & Service Operations Management</em></b>, 25(6), 2268-2276, 2023.
- **Jinjia Huang**,  Stanley Frederick W. T. Lim, M.Serkan. Akturk,  Service Upgrade, Shopper Update: Implications of Adopting 3rd-Party Delivery on Inventory Management, <b><em>Under Revision (R&R decision) at Management Science</em></b>, 2024.
 - **Jinjia Huang**, Zhenzhen Yan, Mabel C. Chou,  Chung-Piaw Teo, The Paradox of Choice: Why Less Can Be More in Decentralized Resource Sharing System, <b><em>Under Review at Manufacturing & Service Operations Management</em></b>, 2024.
 - 
<span class='anchor' id='-projects'></span>
#  Projects
## <span style="color: blue;">Part 1---Strategic Network Design: A Little Flexibility Is All You Need</span>
 - **Jinjia Huang**, Mabel C. Chou,  Chung-Piaw Teo, [Bike-repositioning Using Volunteers: Crowd Sourcing with Choice Restriction](https://ojs.aaai.org/index.php/AAAI/article/view/17407), <b><em>In Proceedings of the AAAI Conference on Artificial Intelligence</em></b>, 35(13), 11844-11852, 2021.
<div class='paper-box'><div class='paper-box-image' style="margin-top: -1.0em; padding-top: 0; margin-bottom: 0"><div><img src='/images/F5_AAAI.jpg' alt="sym" width="100%" style="height:100%"></div></div>
<div class='paper-box-text' markdown="1" style="margin-top: -2.0em; padding-top: 0; margin-bottom: 0">
[**Research**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We study the use of registered volunteers to re-position empty bikes for riders in a bike sharing system.
- We solve a transshipment network design model to account for random route demand and construct a sparse structure that limits volunteer re-balancing to essential routes.
- This provide new insights into the performance of sparse structures in bike re-balancing, showing that concentrating flows reduces redundant moves significantly with minimal impact on demand satisfaction.
</div>
</div>  

 - **Jinjia Huang**, Zhenzhen Yan, Mabel C. Chou,  Chung-Piaw Teo, The Paradox of Choice: Why Less Can Be More in Decentralized Resource Sharing System, <b><em>Under Review at Manufacturing & Service Operations Management</em></b>, 2024.
<div class='paper-box'><div class='paper-box-image' style="margin-top: -1.0em; padding-top: 0; margin-bottom: 0"><div><img src='/images/F0_WebAppDashBoard_Sep2024.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="margin-top: -2.0em; padding-top: 0; margin-bottom: 0">
[**Research**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We develop a novel network design model for repositioning operations, leveraging conic programming and distributionally robust optimization. 
- We provide arguably the first study on constructing sparse networks in decentralized deployment with choice behavior.
- We reveal a paradoxical phenomenon: sometimes, <em> less (choices) can be more (efficient)</em>. We provide new sights into the value of sparse structures.
</div>
</div> 

## <span style="color: blue;">Part 2---Hub Operations: Robustness Boosts Efficiency</span>

 - **Jinjia Huang**, Chung-Piaw Teo, Fan Wang, Zhou Xu, [Buffer Times Between Scheduled Events in Resource Assignment Problem: A Conflict-Robust Perspective](https://iora.nus.edu.sg/wp-content/uploads/2023/06/ConflictRobustPaper_JinjiaHuang.pdf), <b><em>Manufacturing & Service Operations Management</em></b>, 25(6), 2268-2276, 2023.

<div class='paper-box'><div class='paper-box-image' style="margin-top: -1.0em; padding-top: 0; margin-bottom: 0"><div><img src='/images/F1_ConflictRobust.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="margin-top: -2.0em; padding-top: 0; margin-bottom: 0">
[**Research**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We address the fundamental resource assignment problem faced by hub operators managing multiple services with scheduled starting and completion times, accounting for uncertain delays revealed over time.
- We derive a new insight that conflicts and crossings are equivalent under worst-case delay realization.
- This provides the first theoretical explanation, from the perspective of (distributionally) robust optimization for the good performance of the buffering approach in minimizing both crossings and conflicts in the
operations.
</div>
</div>  

 - **Jinjia Huang**, Chung-Piaw Teo, Buffer Inventory Optimization for Dynamic Cross Docking for Uncertain Arrival Sequence, <b><em>Draft completed. Target Journal: Production and Operations Management</em></b>, 2024.

<div class='paper-box'><div class='paper-box-image' style="margin-top: -1.0em; padding-top: 0; margin-bottom: 0"><div><img src='/images/F3_BufferInventoryOptEngine.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="margin-top: -2.0em; padding-top: 0; margin-bottom: 0">
[**Research & Project**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We aim at improving dynamic cross-docking at hubs, such as Singapore's port free-trade zone, in collaboration with IDSC consultancy.
- We use a semi-definite programming (SDP) model to optimize buffer inventory, addressing uncertainties in arrival sequences, supply, and demand, thereby streamlining cross-docking.
- Our work leads to the development of the [LogXHub system](https://appbyjinjiahuang.shinyapps.io/Demo1_DynamicPlanningSystemforCrossDockingOperations_Beta_v9/).
</div>
</div>  


 - **Jinjia Huang**, Chung-Piaw Teo, Mabel C.Chou,  Data Driven Inventory Modeling for Spare Parts in the MRO industry, <b><em>Manuscript in preparation. Target Journal: Production and Operations Management</em></b>, 2024.

<div class='paper-box'><div class='paper-box-image' style="margin-top: -1.0em; padding-top: 0; margin-bottom: 0"><div><img src='/images/F4_KomatsuMultiEchelonInventoryOptEngine.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="margin-top: -2.0em; padding-top: 0; margin-bottom: 0">
[**Research & Project**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We partnered with Komatsu, a leading machinery manufacturer, to address multi-echelon inventory management for spare parts in a one-warehouse, multiple-distributor system.
- We jointly optimize inventory control for intermittent demand at the distributor level and warehouse inventory decisions.
</div>
</div>  

## <span style="color: blue;">Part 3---End-to-End Decision Making: Benefits of Data Pooling</span>

 - **Jinjia Huang**,  Mabel C. Chou, Chung-Piaw Teo,  Graph Neural Network: Forecasting and Replenishment Planning, <b><em>Submitting to Production and Operations Management soon</em></b>, 2024.

<div class='paper-box'><div class='paper-box-image' style="margin-top: -1.0em; padding-top: 0; margin-bottom: 0"><div><img src='/images/F6_JPO.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="margin-top: -2.0em; padding-top: 0; margin-bottom: 0">
[**Research & Project**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We explore the use of a class of Graph Neural Network (GNN) in modeling and exploiting the correlated demand patterns in multiple time series data. 
- We describe an application of GNN approach on a printer service management problem posed by an industry collaborator.
- This project leads to the development of the Joint Prediction and Optimization (JPO) system for demand forecasting and inventory control. The JPO system beta v1.0 was launched on August 29, 2024, for
internal use at NUS and has been used in undergraduate course teaching exercises.
- We provide the novel insight that GNNs might benefit from the data pooling effect inherent to a statistical phenomenon.
</div>
</div>  

- **Jinjia Huang**,  Stanley Frederick W. T. Lim, M.Serkan. Akturk,  Service Upgrade, Shopper Update: Implications of Adopting 3rd-Party Delivery on Inventory Management, <b><em>Under Revision (R&R decision) at Management Science</em></b>, 2024.

<div class='paper-box'><div class='paper-box-image' style="margin-top: -1.0em; padding-top: 0; margin-bottom: 0"><div><img src='/images/F2_RetailingEmpiricalStudy.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="margin-top: -2.0em; padding-top: 0; margin-bottom: 0">
[**Research**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We study the impact of third-party grocery delivery adoption on retail operations using a stylized model, store-level transaction data (in the hundreds of millions), and a DiD synthetic control method.
- We reveal that platform entry significantly increases sales dispersion, reduces popular product sales and volume, while leaving revenue unchanged.
- We derive a new insight that applying inventory pooling to account for sales dispersion changes can improve warehouse-level ordering decisions and mitigate stock imbalances.
</div>
</div>  

## <span style="color: blue;">Part 4---Ongoing Projects</span>
- <b> Application of Generative AI for Airline Demand Forecasting and Seat Pricing: </b> Joint work with SIA Lab, NUS in Singapore.
- <b> Automated Bus Depot Parking Lot Allocation: </b> Joint work with SBS Transit Ltd in Singapore
- <b> Predicting Personalized Surgical Risk and Repair for Cleft Lip and Palate via Computer Vision: </b> Joint work with GuiYang People’s Hospital in China 
- <b> Inventory Control and Order Fulfillment for Jerome’s Furniture: </b> Inventory Control and Order Fulfillment for Jerome’s Furniture in USA



<span class='anchor' id='-academic-experience'></span>
#  Academic Experience
- August 2018 - Present, Senior Research Fellow, IORA, NUS.
- July 2016 - April 2018, Visiting Ph.D. student in DAO, NUS. 

<span class='anchor' id='-educations'></span>
#  Educations
- Ph.D. in Management Science and Engineering, 2018, Sun Yat-sen University, Guangzhou, China. 
- B.Eng. in Intelligent Transportation System, 2012, Sun Yat-sen University, Guangzhou, China. 

<span class='anchor' id='-teaching'></span>
#  Teaching
- Guest lecture on “Forecasting” for third-year undergraduates at NUS (March 2022)
- Guest lectures for a summer camp on “Advanced Application of Python” and “LangChain and LLM” for undergraduates (August 2024)

<span class='anchor' id='-conference-presentations'></span>
#  Conference Presentations
- <b> INFORMS: </b> 2023,2024
- <b> POMS: </b> 2023
- <b> POMS-HK: </b> 2018,2023,2024
- <b> DSI: </b> 2019, 2022
- <b> AAAI: </b> 2021


