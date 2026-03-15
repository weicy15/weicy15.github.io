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

<div class="hero-intro">
  <p class="hero-intro__main">
    <strong class="hero-intro__name">韦淳于</strong>，博士，硕士生导师。中国人民大学信息学院讲师，中国人民大学国家治理大数据和人工智能创新平台研究员。
  </p>
  <p class="hero-intro__sub">
    2019年于清华大学自动化系获学士学位，2024年于清华大学自动化系获博士学位。在博士期间，以第一作者发表高水平论文十三篇，研究成果在腾讯、阿里和快手等公司落地。
  </p>
</div>

<div class="research-section">
  <h3 class="section-title">
    <span class="section-title__icon">🔬</span> 研究领域：关系智能 <span class="section-title__en">(Relational Intelligence)</span>
  </h3>
  
  <p class="research-section__desc">
    关系智能是理解和建模复杂系统中多层次关系结构的科学范式，涵盖以下四个层次：
  </p>
  
  <div class="level-grid">
    <div class="level-card">
      <img src="images/token-level.png" alt="Token-level" class="level-card__icon" style="width:52px;height:52px;max-width:52px;">
      <div class="level-card__body">
        <div class="level-card__label">Token-level</div>
        <div class="level-card__text">语义空间中的符号关联与知识表征</div>
      </div>
    </div>
    <div class="level-card">
      <img src="images/entity-level.png" alt="Entity-level" class="level-card__icon" style="width:52px;height:52px;max-width:52px;">
      <div class="level-card__body">
        <div class="level-card__label">Entity-level</div>
        <div class="level-card__text">知识图谱中的实体关联与推理机制</div>
      </div>
    </div>
    <div class="level-card">
      <img src="images/node-level.png" alt="Node-level" class="level-card__icon" style="width:52px;height:52px;max-width:52px;">
      <div class="level-card__body">
        <div class="level-card__label">Node-level</div>
        <div class="level-card__text">图网络中的节点交互与传播动力学</div>
      </div>
    </div>
    <div class="level-card">
      <img src="images/agent-level.png" alt="Agent-level" class="level-card__icon" style="width:52px;height:52px;max-width:52px;">
      <div class="level-card__body">
        <div class="level-card__label">Agent-level</div>
        <div class="level-card__text">多智能体系统中的协作与博弈行为</div>
      </div>
    </div>
  </div>
  
  <hr style="border: none; border-top: 1px solid #e8e8e8; margin: 20px 0 20px;">

  <h3 class="section-title">
    <span class="section-title__icon">📂</span> 研究项目
  </h3>
  
  <div class="project-card">
    <h4 class="project-card__title">1. 知识增强的大语言模型</h4>
    <ul class="project-card__list">
      <li><strong>上下文知识</strong>：检索增强（RAG）</li>
      <li><strong>参数知识</strong>：知识编辑（Knowledge Editing）</li>
      <li><strong>个性化</strong>：模型个性化（Personalization）</li>
    </ul>
  </div>
  
  <div class="project-card">
    <h4 class="project-card__title">2. 拓扑感知的数据基础模型</h4>
    <ul class="project-card__list">
      <li><strong>建模</strong>：图数据合成（Data Generation）</li>
      <li><strong>预测</strong>：图表征学习（Representation Learning）</li>
      <li><strong>仿真</strong>：多智能体交互（Multi-agent Collaboration）</li>
      <li><strong>计算</strong>：图基础模型（Foundation Model）</li>
    </ul>
  </div>
</div>

<div class="join-us-card">
  <h3 class="join-us-card__title">📢 加入我们</h3>
  <p class="join-us-card__text">
    欢迎有意<strong>科研实习</strong>、攻读<strong>硕士</strong>、攻读<strong>博士</strong>（与陈跃国教授合作指导）的同学联系！
  </p>
  <a href="mailto:weichunyu@ruc.edu.cn" class="btn-contact">
    ✉️ weichunyu@ruc.edu.cn
  </a>
</div>

---

# 🔥 News
- *2025.11*: 获批SMP-清智大模型基金
- *2025.11*: 获批CAAI-蚂蚁科研基金（AGI专项）
- *2025.09*: 获北京市“数据要素X”大赛数据先锋奖
- *2025.08*: 获批国家自然科学基金青年科学基金项目（C类）
- *2024.08*: 正式加入中国人民大学信息学院，担任讲师
- *2024.06*: 取得清华大学工学博士学位🎉


# 📝 Publications (Selected)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/CF-RAG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Counterfactual Reasoning for Retrieval-Augmented Generation

Huaiyu Qin, <span style="font-size: 1.2em;">**Chunyu Wei**</span><sup>✉</sup>, Yueguo Chen, Yunhai Wang

*The International Conference on Learning Representations (ICLR), 2026.* <span style="color:blue">(CCF-A)</span>

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2026</div><img src='images/BAED.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Balanced Anomaly-guided Ego-graph Diffusion Model for Inductive Graph Anomaly Detection](https://arxiv.org/pdf/2602.05232)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Siyuan He, Yu Wang, Yueguo Chen, Yunhai Wang, Bing Bai, Yidong Zhang, Yong Xie, Shunming Zhang, Fei Wang.

*SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2026.* <span style="color:blue">(CCF-A)</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TSC 2026</div><img src='images/GDMSR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Graph-based Diffusion Model for Service Recommendation](https://ieeexplore.ieee.org/abstract/document/11311124)

Xuan Zhang, Xiang Deng, Hongxing Yuan, <span style="font-size: 1.2em;">**Chunyu Wei**</span><sup>✉</sup>, Yushun Fan<sup>✉</sup>, Jia Zhang.

*IEEE Transactions on Services Computing (TSC)* <span style="color:blue">(CCF-A)</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/T-Retriever.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[T-Retriever: Tree-based Hierarchical Retrieval Augmented Generation for Textual Graphs](https://arxiv.org/pdf/2601.04945)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Huaiyu Qin, Siyuan He, Yunhai Wang, Yueguo Chen.

*AAAI Conference on Artificial Intelligence (AAAI), 2026.* <span style="color:blue">(CCF-A)</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2026</div><img src='images/Unicoon.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Unicoon: Hypergraph-based Multi-Agent Simulation of Information Cocoons

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Yongsiqi Tu, Yunhai Wang.

*THE ACM Web Conference (WWW), 2026.* <span style="color:blue">(CCF-A)</span>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/GraphChain.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GraphChain: Large Language Models for Large-scale Graph Analysis via Tool Chaining](https://arxiv.org/pdf/2511.00457)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Wenji Hu, Xingjia Hao, Xin Wang, Yifan Yang, Yunhai Wang, Yang Tian, Yueguo Chen.

*Conference on Neural Information Processing Systems (NeurIPS), 2025.* <span style="color:blue">(CCF-A)</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/CGADM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Conditional Diffusion Anomaly Modeling on Graphs

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Haozhe Lin, Yueguo Chen, Yunhai Wang.

*Conference on Neural Information Processing Systems (NeurIPS), 2025.* <span style="color:blue">(CCF-A)</span>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2025</div><img src='images/GEL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Graph Evidential Learning for Anomaly Detection](https://arxiv.org/pdf/2506.00594)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Wenji Hu, Xingjia Hao, Yunhai Wang, Yueguo Chen, Bing Bai, Fei Wang.

*SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2025.* <span style="color:blue">(CCF-A)</span>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TSC 2024</div><img src='images/CGA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cross-view Graph Alignment for Mashup Recommendation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10542468)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Yushun Fan, Zhixuan Jia, Jia Zhang.

*IEEE Transactions on Services Computing (TSC)* <span style="color:blue">(CCF-A)</span>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/GigaTraj.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GigaTraj: Predicting Long-term Trajectories of Hundreds of Pedestrians in Gigapixel Complex Scenes](https://openaccess.thecvf.com/content/CVPR2024/papers/Lin_GigaTraj_Predicting_Long-term_Trajectories_of_Hundreds_of_Pedestrians_in_Gigapixel_CVPR_2024_paper.pdf)

Haozhe Lin *, <span style="font-size: 1.2em;">**Chunyu Wei**</span> *, Li He *, Yuchen Guo, Yuchy Zhao, Shanglong Li, Lu FANG.

*Conference on Computer Vision and Pattern Recognition (CVPR), 2024.* <span style="color:blue">(CCF-A)</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2023</div><img src='images/MGL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Meta Graph Learning for Long-tail Recommendation](https://dl.acm.org/doi/pdf/10.1145/3580305.3599428)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Jian Liang, Di Liu, Zehui Dai, Mang Li, Fei Wang.

*SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2023.* <span style="color:blue">(CCF-A)</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2023</div><img src='images/GCS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Boosting Graph Contrastive Learning via Graph Contrastive Saliency](https://proceedings.mlr.press/v202/wei23c/wei23c.pdf)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Yu Wang, Bing Bai, Kai Ni, David J. Brady, Lu FANG.

*International Conference on Machine Learning (ICML), 2023.* <span style="color:blue">(CCF-A)</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNSM 2023</div><img src='images/DRGL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Relation Graph Learning for Time-aware Service Recommendation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10288141)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Yushun Fan, Jia Zhang, Zhixuan Jia, Ruyu Yan. 

*IEEE Transactions on Network and Service Management (TSNM).* 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022</div><img src='images/CGI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Contrastive Graph Structure Learning via Information Bottleneck for Recommendation](https://proceedings.neurips.cc/paper_files/paper/2022/file/803b9c4a8e4784072fdd791c54d614e2-Paper-Conference.pdf)

**Spotlight (<5%)**

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Jian Liang, Di Liu, Fei Wang.

*Conference on Neural Information Processing Systems (NeurIPS), 2022.* <span style="color:blue">(CCF-A)</span>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2022</div><img src='images/GSL4REC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GSL4Rec: Session-based Recommendations with Collective Graph Structure Learning and Next Interaction Prediction](https://dl.acm.org/doi/pdf/10.1145/3485447.3512085)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Bing Bai, Kun Bai, Fei Wang.

*International World Wide Web Conference (WWW), 2022.* <span style="color:blue">(CCF-A)</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2022</div><img src='images/DHLCF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Hypergraph Learning for Collaborative](https://dl.acm.org/doi/pdf/10.1145/3511808.3557301)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Jian Liang, Bing Bai, Di Liu.

*International Conference on Information and Knowledge Management (CIKM), 2022.* <span style="color:blue">(CCF-B)</span>


</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TSC 2022</div><img src='images/SGHAN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Time-aware Service Recommendation with Social-powered Graph Hierarchical Attention Network](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9852695)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Yushun Fan, Jia Zhang. 

*IEEE Transactions on Services Computing (TSC)* <span style="color:blue">(CCF-A)</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNSM 2022</div><img src='images/HSGNN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[High-order Social Graph Neural Network for Service Recommendation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9810972)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Yushun Fan, Jia Zhang. 

*IEEE Transactions on Network and Service Management (TSNM)*

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICWS 2020</div><img src='images/AHSG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A-HSG: Neural Attentive Service Recommendation based on High-order Social Graph](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9283986)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Yushun Fan, Jia Zhang, Haozhe Lin.

*IEEE International Conference on Web Services (ICWS), 2020.* <span style="color:blue">(CCF-B)</span>

</div>
</div>


# 📖 Educations
<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-item__date">2019.06 - 2024.06</div>
    <div class="timeline-item__content">
      <strong>清华大学</strong>，信息学院自动化系，工学博士
    </div>
  </div>
  <div class="timeline-item">
    <div class="timeline-item__date">2015.09 - 2019.06</div>
    <div class="timeline-item__content">
      <strong>清华大学</strong>，信息学院自动化系，工学学士
      <div class="timeline-item__sub">2016.08 - 2019.06，清华大学，经济学院经济系，经济学学士（第二学位）</div>
      <div class="timeline-item__sub">2017.08 - 2018.01，美国东北大学，计算机学院，计算机科学与技术（交换生）</div>
    </div>
  </div>
</div>

# 💻 Internships
<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-item__date">2023.05 - 2023.11</div>
    <div class="timeline-item__content">北京快手科技有限公司, 中国</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-item__date">2022.07 - 2023.05</div>
    <div class="timeline-item__content">启元实验室, 中国</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-item__date">2021.05 - 2022.06</div>
    <div class="timeline-item__content">阿里巴巴（北京）有限公司, 中国</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-item__date">2020.11 - 2021.03</div>
    <div class="timeline-item__content">腾讯科技（北京）有限公司, 中国</div>
  </div>
</div>

# 🏅 Services
- Reviewer of T-PAMI, TOIS, TNNLS
- PC Member of WWW 2025
