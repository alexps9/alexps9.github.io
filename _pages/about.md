---
permalink: /
title: "Homepage"
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

# 🗺️ About Me

Hello, I'm **Songyang Peng**. My research interests include **Agentic AI**, **Machine Learning System**, and **AI System Security**.

I am an incoming **Ph.D. student (Fall 2026)** in **Computer Science** at the **[University of California, Santa Barbara](https://www.ucsb.edu/)**, where I will be advised by **[Wenbo Guo](https://henrygwb.github.io/)**. I received my **M.S. in Computer Science** from **Fudan University**, where I worked mainly under the guidance of **[Jiarun Dai](https://djrrr.github.io/)** and **[Yuan Zhang](https://yuanxzhang.github.io/)**. I received my **B.S. in Computer Science (Elite Class)** from **Tianjin University**, where I was advised by **[Yu Mei](https://cic.tju.edu.cn/faculty/yumei/index.html)**.

Previously, I worked as a LLM Inference Engineer Intern at **[ByteDance, Ark](https://www.volcengine.com/product/ark)**, mentored by **[Meng Wang](https://mengwangbupt.github.io/)**, contributing to high-performance LLM serving and agent infrastructure. Before that, I was an AI Research Intern at **[Tencent, IEG](https://www.tencent.com/en-us/)**.

# 🔥 News

<div class="news-scroll" markdown="1">

* \[_2026_\] 🎤 I will give an **Oral** talk at **KDD 2026** on *Amour*. See you in Jeju! 🌊
* \[_2026.06_\] 🎓 I successfully defended my master's thesis and graduated! Thanks to my advisors Prof. **[Jiarun Dai](https://djrrr.github.io/)**! 🙏
* \[_2026.05_\] Served as a **reviewer** for the [Second Workshop on Agents in the Wild: Safety, Security, and Beyond](https://agentwild-workshop.github.io/icml2026/) at **ICML 2026**.
* \[_2026_\] 🎉 One paper accepted by **ICML 2026** on Darwinian memory for GUI agent evolution.
* \[_2025_\] 🎉 One paper accepted by **USENIX Security 2026** on agent-based DoS attacks.
* \[_2025.04_\] 🎉 Started as LLM Inference Engineer Intern at **ByteDance**.
* \[_2024.12_\] 🎉 Selected for Tencent's **Game-Engine Computer Graphics Practice Elite Talent Program** as an AI Research Intern. 
* \[_2024_\] 🎉 One paper accepted by **USENIX VehicleSec 2026** on fuzzing-based testing for autonomous driving.

</div>

# 📝 Publications <span class="publications-note"><sup>&#42;</sup> <em>Equal contribution (Co-first authors).</em></span>

* **AgentGuard: An Attribute-Based Access Control Framework for Tool-Use LLM-Based Agent** \[[PDF](https://arxiv.org/pdf/2605.28071)\] \[[GitHub](https://github.com/WhitzardAgent/AgentGuard)\]<br/>
  Jiaqi Luo<sup>&#42;</sup>, **Songyang Peng**<sup>&#42;</sup>, Jiarun Dai, Zhile Chen, Zhuoxiang Shen, Geng Hong, Xudong Pan, Yuan Zhang, Min Yang.<br/>
  <span class="conference-badge conference-preprint">Preprint</span><br/>
  _Stay tunned._

* **Amour: A Latent Dynamical System for Controllable and Stateful Social Interaction in LLMs** \[PDF\]<br/>
  **Songyang Peng**, Ruoyu Fang, Xinfeng Yuan, Haidong Zheng, Zesong Yang, Ruijie Wang, Hongze Mi, Yilan Guo, Linxiao Zhou.<br/>
  <span class="conference-badge conference-kdd-workshop">Agentic AI for Scientific and Societal Advances 26'</span><br/>
  _KDD 2026 Workshop on SciSoc Agents & LLMs_ (**Oral**); manuscript under review.

* **Darwinian Memory: A Training-Free Self-Regulating Memory System for GUI Agent Evolution** \[[PDF](https://arxiv.org/pdf/2601.22528)\]<br/>
  Hongze Mi, Yibo Feng, WenJie Lu, Song Cao, Jinyuan Li, Yanming Li, Xuelin Zhang, Haotian Luo, **Songyang Peng**, He Cui, Tengfei Tian, Jun Fang, Hua Chai, Naiqiang Tan.<br/>
  <span class="conference-badge conference-icml">ICML'26</span><br/>
  In _Proceedings of the International Conference on Machine Learning (ICML)_, 2026.

* **Autonomy Comes with Costs: Detecting Denial-of-Service Vulnerabilities Caused by Resource Abusing in LLM-based Agents** \[[PDF](https://www.usenix.org/system/files/conference/usenixsecurity26/sec26_prepub_luo.pdf)\]<br/>
  Jiaqi Luo, Jiarun Dai, Fengyu Liu, **Songyang Peng**, Youkun Shi, Tong Bu, Geng Hong, Xudong Pan, Yuan Zhang.<br/>
  <span class="conference-badge conference-usenix-security">USENIX Security'26</span><br/>
  In _Proceedings of the 35th USENIX Security Symposium (USENIX Security)_, Baltimore, MD, USA, August 12-14, 2026.

* **APSFUZZ: Simulation-Based Fuzzing Testing for Automated Parking Systems** \[[PDF](https://www.usenix.org/system/files/vehiclesec25-bu.pdf)\]<br/>
  Tong Bu, Jiarun Dai, Jiaqi Luo, **Songyang Peng**, Zongan Huang, Min Yang.<br/>
  <span class="conference-badge conference-vehiclesec">VehicleSec'25</span><br/>
  In _Proceedings of the 3rd USENIX Symposium on Vehicle Security and Privacy (VehicleSec)_, 2025, pages 289-296.

* **BHUNTER: Generating Blind-Spot Driving Scenarios for Robustness Testing of Perception Systems** \[PDF\]<br/>
  **Songyang Peng**, Jiarun Dai, Yanghao Lv, Jiaqi Luo, Zongan Huang, Yuan Zhang, Min Yang.<br/>
  <span class="conference-badge conference-tosem">TOSEM'26</span><br/>
  _ACM Transactions on Software Engineering and Methodology (TOSEM)_, major revision.

* **Facilitating Logical Flaw Detection for Autonomous Driving Systems through LLM-Empowered Oracle Generation** \[PDF\]<br/>
  Zongan Huang, Jiarun Dai, Jiaqi Luo, Qifan Xiao, **Songyang Peng**, Xudong Pan, Yuan Zhang, Min Yang.<br/>
  <span class="conference-badge conference-tifs">IEEE TIFS'26</span><br/>
  _IEEE Transactions on Information Forensics and Security (TIFS)_, major revision.

# 📖 Education

* _Fall 2026 (incoming)_, **Ph.D. in Computer Science**, University of California, Santa Barbara. Advisor: **[Wenbo Guo](https://henrygwb.github.io/)**.
* _2023.09 - 2026.06_, **M.S. in Computer Science**, Fudan University, School of Computer Science and Technology, Shanghai, China. Advisors: **[Jiarun Dai](https://djrrr.github.io/)**, **[Yuan Zhang](https://yuanxzhang.github.io/)**.
* _2019.09 - 2023.06_, **B.S. in Computer Science (Elite Class)**, Tianjin University, School of Future Technology, Tianjin, China. Advisor: **[Yu Mei](https://cic.tju.edu.cn/faculty/yumei/index.html)**.

# 🏆 Selected Competitions

* 2021, Mathematical Contest in Modeling (MCM) **Honorable Mention**.
* 2020, **1st Prize** in [China Collegiate Intelligent Robot Innovation Competition](https://compeition-excute.oss-cn-beijing.aliyuncs.com/edit/2020128/d566fa3724efd58f005f496eae128590/hqITo26V_1607437732597/%E7%AC%AC%E4%B8%89%E5%B1%8A%E4%B8%AD%E5%9B%BD%E9%AB%98%E6%A0%A1%E6%99%BA%E8%83%BD%E6%9C%BA%E5%99%A8%E4%BA%BA%E5%88%9B%E6%84%8F%E5%A4%A7%E8%B5%9B%E8%8E%B7%E5%A5%96%E5%90%8D%E5%8D%95%E5%85%AC%E7%A4%BA.pdf).

# 💻 Internships

* _2025.04 - 2025.10_, **LLM Inference Engineer Intern**, ByteDance (Ark), Shanghai, China. Mentor: **[Meng Wang](https://mengwangbupt.github.io/)**.
* _2024.12 - 2025.03_, **AI Research Intern, Game & Engine Intelligence**, Tencent IEG, Shanghai, China.

# 🤝 Professional Service

* **Workshop reviewer**, [Agents in the Wild](https://agentwild-workshop.github.io/icml2026/) (ICML 2026), May 2026.
