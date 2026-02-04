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

<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 30px; border-radius: 15px; margin-bottom: 30px; box-shadow: 0 10px 30px rgba(0,0,0,0.15);">
  <div style="background: rgba(255,255,255,0.95); padding: 25px; border-radius: 12px; border-left: 5px solid #667eea;">
    <h2 style="color: #667eea; margin-top: 0; font-weight: bold; font-size: 1.8em;">韦淳于 | Chunyu Wei</h2>
    <p style="color: #2c3e50; font-size: 1.1em; line-height: 1.8; margin-bottom: 15px;">
      <strong>博士，硕士生导师</strong><br>
      中国人民大学信息学院 讲师<br>
      中国人民大学国家治理大数据和人工智能创新平台 兼职研究员
    </p>
    <div style="background: linear-gradient(to right, #f8f9fa 0%, #e9ecef 100%); padding: 15px; border-radius: 8px; margin-top: 15px;">
      <p style="margin: 0; color: #495057; font-size: 0.95em;">
        🎓 2019年于<strong>清华大学自动化系</strong>获学士学位<br>
        🎓 2024年于<strong>清华大学自动化系</strong>获博士学位<br>
        📝 博士期间以第一作者发表<strong style="color: #667eea;">高水平论文十三篇</strong><br>
        🏢 研究成果在<strong>腾讯、阿里、快手</strong>等头部企业落地应用
      </p>
    </div>
  </div>
</div>

<div style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); padding: 3px; border-radius: 12px; margin-bottom: 30px;">
  <div style="background: white; padding: 25px; border-radius: 10px;">
    <h2 style="color: #f5576c; border-bottom: 3px solid #f5576c; padding-bottom: 10px; margin-top: 0;">
      🔬 关系智能 (Relational Intelligence)
    </h2>
    <p style="color: #2c3e50; font-size: 1.05em; line-height: 1.8; font-style: italic; margin-bottom: 20px;">
      致力于解析和建模复杂系统中的多层次关系结构，从微观的<strong>符号关联</strong>到宏观的<strong>智能体协同</strong>，构建统一的关系智能理论框架
    </p>
    
<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px; margin-top: 20px;">
      <div style="background: linear-gradient(135deg, #667eea15 0%, #764ba215 100%); padding: 15px; border-radius: 10px; border-left: 4px solid #667eea;">
        <h4 style="color: #667eea; margin-top: 0; margin-bottom: 8px;">🔵 Token-level Relations</h4>
        <p style="margin: 0; font-size: 0.9em; color: #555;">语义空间中的符号关联与知识表征</p>
      </div>
      
      <div style="background: linear-gradient(135deg, #f093fb15 0%, #f5576c15 100%); padding: 15px; border-radius: 10px; border-left: 4px solid #f5576c;">
        <h4 style="color: #f5576c; margin-top: 0; margin-bottom: 8px;">🔴 Entity-level Relations</h4>
        <p style="margin: 0; font-size: 0.9em; color: #555;">知识图谱中的实体关联与推理</p>
      </div>
      
      <div style="background: linear-gradient(135deg, #fa709a15 0%, #fee14015 100%); padding: 15px; border-radius: 10px; border-left: 4px solid #fa709a;">
        <h4 style="color: #fa709a; margin-top: 0; margin-bottom: 8px;">🟠 Node-level Relations</h4>
        <p style="margin: 0; font-size: 0.9em; color: #555;">图网络中的节点交互与传播动力学</p>
      </div>
      
      <div style="background: linear-gradient(135deg, #30cfd015 0%, #33086715 100%); padding: 15px; border-radius: 10px; border-left: 4px solid #30cfd0;">
        <h4 style="color: #30cfd0; margin-top: 0; margin-bottom: 8px;">🟢 Agent-level Relations</h4>
        <p style="margin: 0; font-size: 0.9em; color: #555;">多智能体系统中的协作与博弈</p>
      </div>
    </div>
  </div>
</div>

<div style="background: linear-gradient(to right, #4facfe 0%, #00f2fe 100%); padding: 3px; border-radius: 12px; margin-bottom: 30px;">
  <div style="background: white; padding: 25px; border-radius: 10px;">
    <h2 style="color: #4facfe; margin-top: 0; margin-bottom: 20px;">🎯 具体研究项目</h2>
    
<div style="margin-bottom: 25px;">
      <h3 style="color: #2c3e50; margin-bottom: 15px; font-size: 1.3em;">
        <span style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">
          一、图机器学习 (Graph Machine Learning)
        </span>
      </h3>
      <div style="background: #f8f9fa; padding: 20px; border-radius: 10px; border-left: 5px solid #667eea;">
        <p style="margin: 0 0 10px 0; color: #2c3e50; font-weight: bold;">面向复杂人机系统的多模态图数据智能处理：</p>
        <ul style="margin: 0; padding-left: 25px; color: #495057;">
          <li style="margin-bottom: 8px;"><strong style="color: #667eea;">建模</strong>：图数据合成 (Graph Generation) — 从数据分布中学习生成新的图结构</li>
          <li style="margin-bottom: 8px;"><strong style="color: #764ba2;">预测</strong>：图表征学习 (Graph Representation Learning) — 提取图的低维稠密表示</li>
          <li style="margin-bottom: 8px;"><strong style="color: #f093fb;">仿真</strong>：多智能体交互 (Multi-agent Collaboration) — 模拟复杂系统的动态演化</li>
          <li style="margin-bottom: 0;"><strong style="color: #f5576c;">计算</strong>：图基础模型 (Graph Foundation Model) — 构建统一的图数据处理范式</li>
        </ul>
      </div>
    </div>
    
<div>
      <h3 style="color: #2c3e50; margin-bottom: 15px; font-size: 1.3em;">
        <span style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">
          二、知识增强大模型 (Knowledge-Enhanced LLMs)
        </span>
      </h3>
      <div style="background: #f8f9fa; padding: 20px; border-radius: 10px; border-left: 5px solid #f5576c;">
        <ul style="margin: 0; padding-left: 25px; color: #495057;">
          <li style="margin-bottom: 8px;"><strong style="color: #f093fb;">上下文知识</strong>：检索增强生成 (RAG) — 动态引入外部知识增强推理能力</li>
          <li style="margin-bottom: 8px;"><strong style="color: #f5576c;">参数知识</strong>：知识编辑 (Knowledge Editing) — 精确修正模型内部知识表示</li>
          <li style="margin-bottom: 0;"><strong style="color: #fa709a;">个性化</strong>：模型个性化 (Personalization) — 适配特定场景与用户需求</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<div style="background: linear-gradient(135deg, #fdeb71 0%, #f8d800 100%); padding: 25px; border-radius: 12px; margin-bottom: 30px; text-align: center; box-shadow: 0 8px 20px rgba(248,216,0,0.3);">
  <h2 style="color: #2c3e50; margin: 0 0 15px 0; font-size: 1.6em;">🎓 招生信息</h2>
  <p style="color: #2c3e50; font-size: 1.15em; margin-bottom: 20px; line-height: 1.8;">
    <strong>热烈欢迎</strong>有志于从事前沿科研的优秀学生加入课题组！<br>
    <span style="font-size: 0.95em;">科研实习生 | 硕士研究生 | 博士研究生（与陈跃国教授合作指导）</span>
  </p>
  <a href="https://365.kdocs.cn/l/chw2voSTrowu" style="display: inline-block; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 12px 35px; border-radius: 25px; text-decoration: none; font-weight: bold; font-size: 1.1em; box-shadow: 0 4px 15px rgba(102,126,234,0.4); transition: transform 0.3s;">
    📋 查看详细招生介绍
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

*The International Conference on Learning Representations (ICLR), 2026.* <span style="color:blue">(CAAI-A)</span>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2026</div><img src='images/Unicoon.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Unicoon: Hypergraph-based Multi-Agent Simulation of Information Cocoons

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Yongsiqi Tu, Yunhai Wang.

*THE ACM Web Conference (WWW), 2026.* <span style="color:blue">(CCF-A)</span>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2026</div><img src='images/BAED.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Balanced Anomaly-guided Ego-graph Diffusion Model for Inductive Graph Anomaly Detection

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Siyuan He, Yu Wang, Yueguo Chen, Yunhai Wang, Bing Bai, Yidong Zhang, Yong Xie, Shunming Zhang, Fei Wang.

*SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2026.* <span style="color:blue">(CCF-A)</span>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/T-Retriever.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[T-Retriever: Tree-based Hierarchical Retrieval Augmented Generation for Textual Graphs](https://arxiv.org/pdf/2601.04945)

<span style="font-size: 1.2em;">**Chunyu Wei**</span>, Huaiyu Qin, Siyuan He, Yunhai Wang, Yueguo Chen.

*AAAI Conference on Artificial Intelligence (AAAI), 2026.* <span style="color:blue">(CCF-A)</span>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TSC 2026</div><img src='images/GDMSR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Graph-based Diffusion Model for Service Recommendation

Xuan Zhang, Xiang Deng, Hongxing Yuan, <span style="font-size: 1.2em;">**Chunyu Wei**</span><sup>✉</sup>, Yushun Fan<sup>✉</sup>, Jia Zhang.

*IEEE Transactions on Services Computing (TSC)* <span style="color:blue">(CCF-A)</span>

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
- *2019.06 - 2024.06*, 清华大学，信息学院自动化系，工学博士 
- *2015.09 - 2019.06*, 清华大学，信息学院自动化系，工学学士 
    - *2016.08 - 2019.06*, 清华大学，经济学院经济系，经济学学士（第二学位）
    - *2017.08 - 2018.01*, 美国东北大学, 计算机学院, 计算机科学与技术（交换生）

# 💻 Internships
- *2023.05 - 2023.11*, 北京快手科技有限公司, 中国
- *2022.07 - 2023.05*, 启元实验室, 中国
- *2021.05 - 2022.06*, 阿里巴巴（北京）有限公司, 中国
- *2020.11 - 2021.03*, 腾讯科技（北京）有限公司, 中国

# 🏅 Services
- Reviewer of T-PAMI, TOIS, TNNLS
- PC Member of WWW 2025
