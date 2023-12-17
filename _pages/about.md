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

Hey, my name is **Hongbin Pei (裴红斌)**, an assistant professor at School of Cyber Science and Engineering, Xi'an Jiaotong University (西安交通大学). I received B.Sc, M.Eng, and Ph.D. degree from  the College of Computer Science and Technology, Jilin University (吉林大学). My research interest focuses on Machine Learning and Complex Networks.
I published several papers at the top international AI conferences and journals, such as IEEE TPAMI, ICLR, NeurIPS.


# 🔥 News
- *2023.12*: &nbsp;🎉🎉 We got two papers accepted for presentation at AAAI'24
- *2023.12*: &nbsp;🎉🎉 I participated in and delivered a talk at the Xiangshan Science Conference (香山科学会议)
- *2022.08*: &nbsp;🎉🎉 Our "On the Dimension and Metric of Network Embedding" project is selected to be awarded by NSFC, grant 62202369
- *2021.08*: &nbsp;🎉🎉 I join Xi'an Jiaotong University as a Tenure-Track Assistant Professor. 
- *2021.06*: &nbsp;🎉🎉 I receive Ph.D. degree from Jilin University.

# 📝 Publications 

## <font color=grey>Featured Publications</font>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2020</div><img src='images/iclr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Geom-GCN: Geometric Graph Convolutional Networks](https://openreview.net/pdf?id=S1e2agrFvS)   [**Code**](https://github.com/graphdml-uiuc-jlu/geom-gcn) 

**Hongbin Pei**, Bingzhe Wei, Kevin Chen-Chuan Chang, Yu Lei, Bo Yang. The International Conference on Learning Representations (ICLR), 2020 

**Key contribution:** **We point out two fundamental weaknesses of message-passing neural network**, *i.e.*., losing the structural information of nodes in neighborhoods and lacking the ability to capture long-range dependencies in disassortative graphs. 
  
The paper is the first work to raise the problem of graph learning heterophily, and gains more than <a href='https://scholar.google.com/citations?user=FxVmazsAAAAJ&hl'>google scholar citations <strong><span id='total_cit'>700+</span></strong></a>.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TPAMI</div><img src='images/tpami2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Active Surveillance via Group Sparse Bayesian Learning](https://ieeexplore.ieee.org/document/9193963)  [**Code**](https://github.com/hp17illinois/Active-Surveillance-via-Group-Sparse-Bayesian-Learning) 

**Hongbin Pei**, Bo Yang, Jiming Liu, Kevin Chen-Chuan Chang. IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2022  

**Key contribution:** We formulate the active surveillance task as a row sparse sentinel network mining problem for the first time. 
  **We apply the proposed active surveillance algorithm into malaria surveillance in border areas of China and Myanmar, which played a crucial role in the elimination of malaria in Yunnan**.
  
  We investigated malaria cases many times in border areas of China and Myanmar; a snapshot is shown on the left.
</div>
</div>

## <font color=grey>Slected Publications</font>

[2023] **Hongbin Pei**, Taile Chen, Chen A, Huiqi Deng, Jing Tao, Pinghui Wang, Xiaohong Guan. HAGO-Net: Hierarchical Geometric  Massage  Passing for Molecular Representation Learning.  Thirty-eighth AAAI Conference on Artificial Intelligence (**AAAI**), 2023  （<span style="color:blue"> **CCF-A** </span>）

[2023] Jinjin Chi, Zhichao Zhang, Zhiyao Yang, Jihong Ouyang, **Hongbin Pei (Corresponding Author)**. Generalized Variational Inference via Optimal Transport.  Thirty-eighth AAAI Conference on Artificial Intelligence (**AAAI**), 2023  （<span style="color:blue"> **CCF-A** </span>）

[2022] **Hongbin Pei**, Bo Yang, Jiming Liu, Kevin Chen-Chuan Chang. Active Surveillance via Group Sparse Bayesian Learning. IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**), 2022 （<span style="color:blue"> **CCF-A** </span>; **impact factor 24.31**; **ESI** Hot Paper (top 0.1%)）

[2022] 王平辉, **裴红斌**, 赵俊舟, 秦涛, 沈超, 刘东亮, 管晓宏. 网络社会现代治理的挑战与对策. 中国科学院院刊, 2022 

[2022] Jialun Liu, Yifan Sun, Feng Zhu, **Hongbin Pei**, Yi Yang, Wenhui Li. Learning Memory-Augmented Unidirectional Metrics for Cross-Modality Person Re-Identification. IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**), 2022 （<span style="color:blue"> **CCF-A** </span>）

[2022] Denghao Ma, Yueguo Chen, Changyu Wang, **Hongbin Pei**, Yitao Zhai, Gang Zheng, Qi Chen. Definition-Augmented Jointly Training Framework for Intention Phrase Mining. 27th international Conference on Database Systems for Advanced Applications (**DASFAA**), 2022 （<span style="color:blue"> **CCF-B** </span>）

[2022] Jialun Liu, Yifan Sun, Yijin Xu, **Hongbin Pei**, Wenhui Li. Feature Cloud: Improving Deep Visual Recognition With Probabilistic Feature Augmentation. IEEE Transactions on Circuits and Systems for Video Technology (**TCSVT**), 2022 （<span style="color:blue"> **CCF-B** </span>）

[2020] **Hongbin Pei**, Bingzhe Wei, Kevin Chen-Chuan Chang, Yu Lei, Bo Yang. Geom-GCN: Geometric Graph Convolutional Networks. The eighth International Conference on Learning Representations (**ICLR**), 2020 （<span style="color:blue"> **Tsinghua University CS-A** </span>; **Spotlight Presentation**）

[2020] **Hongbin Pei**, Bingzhe Wei, Kevin Chen-Chuan Chang, Chunxu Zhang, Bo Yang. Curvature Regularization to Prevent Distortion in Graph Embedding. Thirty-fourth Conference on Neural Information Processing Systems (**NeurIPS**), 2020 （<span style="color:blue"> **CCF-A** </span>; **Spotlight Presentation**）

[2020] Yu Lei, Zhitao Wang, Wenjie Li, **Hongbin Pei**, Quanyu Dai. Social Attentive Deep Q-networks for Recommender Systems. IEEE Transactions on Knowledge and Data Engineering (**TKDE**), 2020 （<span style="color:blue"> **CCF-A** </span>）

[2020] Yu Lei, **Hongbin Pei**, Hanqi Yan, Wenjie Li. Reinforcement learning based recommendation with graph convolutional q-network. 43rd international ACM SIGIR conference on research and development in information retrieval (**SIGIR**), 2020 （<span style="color:blue"> **CCF-A** </span>）

[2019] Yu Lei, Zhitao Wang, Wenjie Li, **Hongbin Pei**. Social attentive deep q-network for recommendation. 42nd international ACM SIGIR conference on research and development in information retrieval (**SIGIR**), 2019 （<span style="color:blue"> **CCF-A** </span>）

[2018] **Hongbin Pei**, Bo Yang, Jiming Liu, Lei Dong. Group Sparse Bayesian Learning for Actively Surveillance on Epidemic Dynamics. Thirty-second AAAI Conference on Artificial Intelligence (**AAAI**), 2018  （<span style="color:blue"> **CCF-A** </span>; **Spotlight Presentation**）

[2017] Bo Yang, **Hongbin Pei**, Hechang Chen, Jiming Liu, Shang Xia. Characterizing and Discovering Spatiotemporal Social Contact Patterns for Healthcare. IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**), 2017 （<span style="color:blue"> **CCF-A** </span>; **impact factor 24.31**）

[2017] Jingbo Zhou, **Hongbin Pei**, Haishan Wu. Early Warning of Human Crowds Based on Query Data from Baidu Map: Analysis Based on Shanghai Stampede. 	arXiv:1603.06780, 2017 （This paper attract widespread attention and is reported by many international media, including [MIT Technology Review (麻省理工科技评论)](https://www.technologyreview.com/2016/03/24/246356/baidu-uses-map-searches-to-predict-when-crowds-will-get-out-of-control/), [Wall Street Journal (华尔街日报)](https://www.wsj.com/articles/BL-CJB-28918), [South China Morning Post (南华早报)](https://www.scmp.com/tech/china-tech/article/1930022/chinese-search-engine-giant-baidu-develops-ai-algorithm-predict) ）

## <font color=grey>译著</font>

《机器学习精讲：基础、算法及应用》杰瑞米·瓦特、雷萨·博哈尼、阿格洛斯·K.卡萨格罗斯. 机械工业出版社. ISBN 9787111611967. 2019 （负责第五章和第六章）


# 🚀  Research Projects

- **国家自然科学基金（青年项目）**，“网络嵌入的维数与度量研究”，62202369，2023-2025 

- **博士后创新人才支持计划（博新计划）**，“大规模动态异质网络表示学习方法与应用”，BX2021240，2021-2023  (全国400人入选，其中计算机学科仅14人)

- **北京交通发展研究院——揭榜挂帅课题**，“基于街景、遥感图像等多源数据的城市用地规模与功能预测及在交通网络的应用”，2022-2023 

- **智能网络与网络安全教育部重点实验室——青年学术骨干培植项目**，“大规模图解耦表示学习方法及应用”，2022-2023

- **符号计算与知识工程教育部重点实验室——开放课题**，“面向3D分子表示学习的层次几何图神经网络”，2022-2024

# 🎖 Honors

- **吉林大学优秀博士学位论文**，2022 

- **吉林省自然科学奖一等奖**，2021

- **全国博士后创新创业大赛优胜奖**，2021 
 
# 🎓 Educations

- *2015.09 - 2021.06*, **Ph.D** in Computer Science and Technology, Jilin University

- *2012.09 - 2015.06*, **M.Eng** in Computer Science and Technology, Jilin University

- *2008.09 - 2012.06*, **B.Sc** in Computer Science and Technology, Jilin University

# 🚢 Visiting Experience 

*2019.01 - 2020.12*, **Visiting Scholar**,  Data and Information Systems Laboratory (DAIS), University of Illinois at Urbana-Champaign (UIUC)

*2016.06 - 2017.06*, **Research Assistant**, Centre for Health Informatics (HIC), Hong Kong Baptist Univeristy (HKBU)

# 🔉 Invited Talks

- *2022.05*, **网络几何**, 生物神经智能—神经网络与图神经网络研讨会, 中国人工智能学会CAAI（在线）

- *2018.05*, **接触跟踪：下一代的传染病防控技术**, 西南大学（重庆）

- *2017.08*, **人类接触时空模式的建模与推断**, 博士生论坛, 中国计算机学会CCF（昆明）

- *2016.11*, **面向边境疟疾控制的主动监控系统**, 中国疾病预防控制中心寄生虫病预防控制所（上海）

# 💻 Services

- *Conference reveiwer*: ICML, ICLR, NeurIPS, AAAI, IJCAI, CVPR, ICCV, KDD, SDM
- *Journal reveiwer*: IEEE TKDE, IEEE TNNLS, IEEE TPAMI, DKE, Scientific Reports

# 📙 Books that inspired me most

- **《超越时空——通过平行宇宙、时间卷曲和第十维度的科学之旅》** by 加来道雄
- **《哲学之树》** by Stephen R. Palmquist
- **《Probably Approximately Correct: Nature's Algorithms for Learning and Prospering in a Complex World》** by Leslie Valiant
- **《背水一战：从纱厂小工到大学校长》** by 孔宪铎

# The beautiful tree of life on earth

We are merely a leaf of the tree; enjoy life! The ability to **Create Knowledge** may be the key to differentiating us from other leaves.

![WechatIMG684](https://user-images.githubusercontent.com/46875212/190320246-a7d711d2-5443-42a1-b3b4-fcc20e71dc2f.jpeg)

The figure was created by Evogeneao.
