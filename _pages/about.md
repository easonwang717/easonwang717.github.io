---
permalink: /
title: "About me"
excerpt: "About me"
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

Yitu Wang is a Ph.D. candidate in computer engineering in Duke ECE Department under the supervision of [Prof. Yiran Chen](https://ece.duke.edu/faculty/yiran-chen). He received B.S.E. in Microelectronics from Fudan University in 2020. His research interests include machine learining acceleration, near data processing for data-intensive applications such recommendation system, approximate nearest neighbor search and retrieval-augemented generation (RAG), and algorithm-architecture co-design for deep learning system. He is expected to gradute in Spring of 2025.

# 📖 Educations
- *2020.08 -*, Ph.D. candidate in Computer Engineering at Duke University.
- *2016.09 - 2020.06*, B.S.E in Microelectronics at Fudan University.

# 💻 Internships
- *2023.05 - 2023.08*, System Architect Intern in [Samsung Memory Solution Lab]([http://nicsefc.ee.tsinghua.edu.cn](https://semiconductor.samsung.com/us/about-us/us-office/us-r-and-d-labs/memory-labs/)), San Jose, California, USA.
- *2022.05 - 2022.08*, System Architect Intern in [Samsung Memory Solution Lab]([http://nicsefc.ee.tsinghua.edu.cn](https://semiconductor.samsung.com/us/about-us/us-office/us-r-and-d-labs/memory-labs/)), San Jose, California, USA.
- *2020.08 - 2021.07*, Research Intern (worked remotely as a Ph.D. student at Duke) in [NICS-EFC](http://nicsefc.ee.tsinghua.edu.cn) Group in Tsinghua EE Department, Beijing, China.
  

# 📝 Publications 
## Preprints
- [In Submission] **Yitu Wang**, Minxue Tang, Hanqiu Chen, Shiyu Li, Andrew Chang, Jie “Callie” Hao, Hai “Helen” Li, Yiran Chen, “FedRepre: End-to-End Acceleration of Federated Learning System with Client Representative”.

## First-author papers
- \[**ISCA'24**\] **Yitu Wang**, Shiyu Li, Qilin Zheng, Linghao Song, Zongwang Li, Andrew Chang, Hai “Helen” Li, Yiran Chen,
"NDSearch: Accelerating Approximate Nearest Neighbor Search through Near-Data Processing". *To appear on 51st
IEEE/ACM Annual International Symposium on Computer Architecture, 2024*.

-\[**DAC'24**\] Hanqiu Chen\*, **Yitu Wang\***, Andrew Chang, Yiran Chen, Cong “Callie” Hao, “ICGMM: CXL-enabled Memory
Expansion with Intelligent Caching Using Gaussian Mixture Model”. *To appear on 61st IEEE/ACM Annual Design
Automation Conference, 2024. (\*equal contribution)*

-\[**ESWEEK’23/TECS’23**\] **Yitu Wang**, Shiyu Li, Qilin Zheng, Andrew Chang, Hai “Helen” Li, Yiran Chen, “[EMS-I: An
Efficient Memory System Design with Specialized Caching Mechanism for Recommendation System](https://dl.acm.org/doi/abs/10.1145/3609384)”. *ACM Transactions on Embedded Computing System, 2023.*

-\[**ICCAD’21**\] **Yitu Wang**, Zhenhua Zhu, Fan Chen, Mingyuan Ma, Guohao Dai, Yu Wang, Hai “Helen” Li, and Yiran Chen,
“[ReRec: In-ReRAM Acceleration with Access-Aware Mapping for Personalized Recommendation](https://ieeexplore.ieee.org/document/9643573)”. *2021 IEEE/ACM International Conference on Computer Aided Design.*

-\[**DATE’20**\] **Yitu Wang**, Fan Chen, Linghao Song, C.J. Richard Shi, Hai “Helen” Li, and Yiran Chen, “[ReBoc: Accelerating
Block-Circulant Neural Networks in ReRAM](https://ieeexplore.ieee.org/document/9116422)”. *2020 Design, Automation & Test in Europe Conference & Exhibition.*

## Co-author papers

-\[**DAC'24**\] Qilin Zheng, Ziru Li, Jonathan Ku, **Yitu Wang**, Brady Taylor, Yiran Chen, “Improving the Efficiency of In-
Memory-Computing Macro with a Hybrid Analog-Digital Computing Mode For Lossless Neural Network Inference”. *To
appear on 61st IEEE/ACM Annual Design Automation Conference, 2024.*

-\[**TC’24**\] Shiyu Li, **Yitu Wang**, Edward Hanson, Andrew Chang, Yang Seok Ki, Hai “Heleln” Li, Yiran Chen, “[NDRec:
Accelerating the Training of Recommendation Models through Near-Data Processing](https://www.computer.org/csdl/journal/tc/2024/05/10437993/1UyVDfWo6Uo)”, *IEEE Transaction on Computers, 2024.*

-\[**ISCAS'24**\] Qilin Zheng, Shiyu Li, **Yitu Wang**, Ziru Li, Hai “Helen” Li, Yiran Chen, “Hybrid Digital/Analog Memoristorbased
Computing Architecture for Sparse Deep Learning Acceleration”. *To appear on 2024 International Symposium on Circuits and Systems.*

-\[**MICRO’23**\] Edward Hanson, Shiyu Li, Guanglei Zhou, Feng Cheng, **Yitu Wang**, Hai “Helen” Li, and Yiran Chen, “[Si-kintusgi: Towards Recovering Golden-like Performance of Defective Many-core Spatial Architecture for AI](https://dl.acm.org/doi/abs/10.1145/3613424.3614278?casa_token=vK8OZUhzCQIAAAAA:lxy9FqzENsymrqXhOhvTzrPecFl5t72Mz7uoXm0oYQ-ZyHy6ZQLe3ccY5qBinfR6m-pOnkVWeK9Oaw)”. *Proceedings of the 56th Annual IEEE/ACM International Symposium on Microarchitecture, 2023.*

-\[**DAC’23**\] Qilin Zheng, Shiyu Li, **Yitu Wang**, Ziru Li, Hai “Helen” Li, and Yiran Chen, “[Accelerating Sparse Attention with
Reconfigurable Non-Volatile Processing-in-Memory Architecture](https://ieeexplore.ieee.org/abstract/document/10247908?casa_token=Y_YA9r7mkPYAAAAA:jrpX-cfCWQ2LZ7jic5_IW_lUXYuGDatyTfZ_xqyGmGL8_BM8LgzoiNc8yph5GUYMYcHRQl7DCcA)”. *60th IEEE/ACM Annual Design Automation Conference, 2023.*

-\[**CVPR’22**\] Minxue Tang, Xuefei Ning, **Yitu Wang**, Yu Wang and Yiran Chen, “[FedGP: Correlation-Based Active Client
Selection for Heterogeneous Federated Learning](https://openaccess.thecvf.com/content/CVPR2022/papers/Tang_FedCor_Correlation-Based_Active_Client_Selection_Strategy_for_Heterogeneous_Federated_Learning_CVPR_2022_paper.pdf)”. *Proceedings of 2022 IEEE/CVF Conference on Computer Vision and Pttern Recognition.*

-\[**EMC2-NeurIPS’19**\] Jingyang Zhang, Huanrui Yang, Fan Chen, **Yitu Wang**, and Hai “Helen” Li, “[Exploring Bit-Slice
Sparsity in Deep Neural Networks for Efficient ReRAM-Based Deployment](https://ieeexplore.ieee.org/document/9463560)”. *Fifth Workshop on Energy Efficient Machine Learning and Cognitive Computing NeurIPS Edition, 2019.*


# 📖 Journal and Conference Reviewer Experiences
CAL, CVPR, TC, TCAD, TCAS-I, TVLSI, TODAES

# 🌍 Visitor Map
<script type="text/javascript" src="//rf.revolvermaps.com/0/0/6.js?i=54e0ojatafc&amp;m=7&amp;c=e63100&amp;cr1=ffffff&amp;f=arial&amp;l=0&amp;bv=90&amp;lx=-420&amp;ly=420&amp;hi=20&amp;he=7&amp;hc=a8ddff&amp;rs=80" async="async"></script>
