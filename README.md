# Hyperbolic Graph Representation Learning: A Review of Methods and Applications

## Introduction

Recently, hyperbolic spaces have emerged as a promising alternative for processing data with a tree-like structure or power-law distribution, owing to its exponential growth property and tree-likeness prior. Different from the Euclidean space, which expands polynomially, the hyperbolic space grows exponentially which makes it gain natural advantages in abstracting tree-like or scale-free data with hierarchical organizations. This repository provides a curated list of articles referenced in the paper “Hyperbolic Graph Representation Learning: A Review of Methods and Applications”, aiming to support researchers and promote community development. For more articles on hyperbolic representations, please refer to our other [repository](https://github.com/marlin-codes/Awesome-Hyperbolic-Representation-and-Deep-Learning?tab=readme-ov-file#content). 
We are aware that there will inevitably be some mistakes and oversights, so if you have any questions or suggestions, please feel free to contact us (menglin.yang[@]outlook.com).

<table>
<tr><td colspan="2"><a href="#surveys" style="color:#B22222">
1. Surveys
</a></td></tr>
<tr><td colspan="2"><a href="#hyperbolic-graph-representation-method" style="color:#B22222">2. Hyperbolic Graph Representation Method</a></td></tr> 
<tr>
    <td>&ensp;<a href="#hyperbolic-initialization">2.1 Hyperbolic Initialization</a></td>
    <td>&ensp;<a href="#hyperbolic-graph-embedding">2.2 Hyperbolic Graph Embedding</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="#GNN-based-hyperbolic-models">2.3 GNN-based Hyperbolic Models</a></td>
    <td>&ensp;<a href="#emerging-hyperbolic-graph-learning-paradigms">2.4 Emerging Hyperbolic Graph Learning Paradigms</a></td>
</tr>
<tr><td colspan="2"><a href="#applications" style="color:#B22222">3. Applications</a></td></tr> 
<tr>
    <td>&ensp;<a href="#recommendation-systems">3.1 Recommendation Systems</a></td>
    <td>&ensp;<a href="#knowledge-graph">3.2 Knowledge Graph</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#bioinformatics-and-molecular-graphs">3.3 Bioinformatics and Molecular Graphs</a></td>
    <td>&ensp;<a href="#other-application-scenarios">3.4 Other Application Scenarios</a></td>
</tr>
</table>

## [Surveys](#content)

1. [Hyperbolic Deep Neural Networks: A Survey](https://arxiv.org/abs/2101.04562) TPAMI 2021 \
Wei Peng, Tuomas Varanka, Abdelrahman Mostafa, Henglin Shi, Guoying Zhao

1. [Hyperbolic Deep Learning in Computer Vision: A Survey](https://link.springer.com/article/10.1007/s11263-024-02043-5) IJCV 2024 \
Pascal Mettes, Mina Ghadimi Atigh, Martin Keller-Ressel, Jeffrey Gu, Serena Yeung


## [Hyperbolic Graph Representation Method](#content)

### [Hyperbolic Initialization](#content)

1. [HGCH: A Hyperbolic Graph Convolution Network Model for Heterogeneous Collaborative Graph Recommendation](https://arxiv.org/abs/2304.02961), CIKM 2024 \
Lu Zhang, Ning Wu

1. [Hyperbolic Graph Convolutional Neural Networks](https://arxiv.org/abs/1910.12933), NeurIPS 2019 \
Ines Chami, Rex Ying, Christopher Ré, Jure Leskovec

1. [Hyperbolic Graph Neural Networks](https://arxiv.org/abs/1910.12892), NeurIPS 2019 \
Qi Liu, Maximilian Nickel, Douwe Kiela

1. [Hyperbolic attention networks](https://arxiv.org/abs/1805.09786), ICLR 2019 \
Caglar Gulcehre, Misha Denil, Mateusz Malinowski, Ali Razavi, Razvan Pascanu, Karl Moritz Hermann, Peter Battaglia, Victor Bapst, David Raposo, Adam Santoro, Nando de Freitas

### [Hyperbolic Graph Embedding](#content)

**Distance-based Methods**
1. [Poincaré Embeddings for Learning Hierarchical Representations](https://arxiv.org/abs/1705.08039), NeurIPS 2017 \
Maximilian Nickel, Douwe Kiela

1. [Learning Continuous Hierarchies in the Lorentz Model of Hyperbolic Geometry](https://arxiv.org/abs/1806.03417), ICML 2018 \
Maximilian Nickel, Douwe Kiela

1. [Lorentzian Distance Learning for Hyperbolic Representations](https://proceedings.mlr.press/v97/law19a.html), ICML 2019 \
Marc Law, Renjie Liao, Jake Snell, Richard Zemel

1. [Learning Mixed-Curvature Representations in Product Spaces](https://openreview.net/forum?id=HJxeWnCcF7), ICLR 2019 \
Albert Gu, Frederic Sala, Beliz Gunel, Christopher Ré

**Angle-based Methods**
1. [Hyperbolic Entailment Cones for Learning Hierarchical Embeddings](https://arxiv.org/abs/1804.01882), ICML 2018 \
Octavian-Eugen Ganea, Gary Bécigneul, Thomas Hofmann

1. [Modeling Heterogeneous Hierarchies with Relation-specific Hyperbolic Cones](https://arxiv.org/abs/2110.14923), NeurIPS 2021 \
Yushi Bai, Rex Ying, Hongyu Ren, Jure Leskovec

1. [Shadow Cones: A Generalized Framework for Partial Order Embeddings](https://arxiv.org/abs/2305.15215), ICLR 2024 \
Tao Yu, Toni J.B. Liu, Albert Tseng, Christopher De Sa

**Disk-based Methods**
1. [Hyperbolic Disk Embeddings for Directed Acyclic Graphs](https://arxiv.org/abs/1902.04335), ICML 2019 \
Ryota Suzuki, Ryusuke Takahama, Shun Onoda

### [GNN-based Hyperbolic Models](#content)

**Tangent Space-based Models**
1. [Hyperbolic Graph Neural Networks](https://arxiv.org/abs/1910.12892), NeurIPS 2019 \
Qi Liu, Maximilian Nickel, Douwe Kiela

1. [Hyperbolic Graph Convolutional Neural Networks](https://arxiv.org/abs/1910.12933), NeurIPS 2019 \
Ines Chami, Rex Ying, Christopher Ré, Jure Leskovec

1. [Hyperbolic Temporal Network Embedding](https://ieeexplore.ieee.org/document/9999499), TKDE 2022 \
Menglin Yang, Min Zhou, Hui Xiong, Irwin King

1. [Lorentzian Graph Convolutional Networks](https://arxiv.org/abs/2104.07477), WWW 2021 \
Yiding Zhang, Xiao Wang, Chuan Shi, Nian Liu, Guojie Song

**Fully Hyperbolic Models**
1. [Fully Hyperbolic Neural Networks](https://arxiv.org/abs/2105.14686), ACL 2022 \
Weize Chen, Xu Han, Yankai Lin, Hexu Zhao, Zhiyuan Liu, Peng Li, Maosong Sun, Jie Zhou

1. [A Hyperbolic-to-Hyperbolic Graph Convolutional Network](https://arxiv.org/abs/2104.06942), CVPR 2021 \
Jindou Dai, Yuwei Wu, Zhi Gao, Yunde Jia

1. [Fully Hyperbolic Graph Convolution Network for Recommendation](https://arxiv.org/abs/2108.04607), CIKM 2021 \
Liping Wang, Fenyu Hu, Shu Wu, Liang Wang

1. [Hyperbolic Neural Networks++](https://arxiv.org/abs/2006.08210), ICLR 2021 \
Ryohei Shimizu, Yusuke Mukuta, Tatsuya Harada

**Neighborhood Aggregation Mechanism**
1. [kHGCN: Tree-likeness Modeling via Continuous and Discrete Curvature Learning](https://arxiv.org/abs/2212.01793), KDD 2023 \
Menglin Yang, Min Zhou, Lujia Pan, Irwin King

1. [Hyperbolic Graph Attention Network](https://arxiv.org/abs/1912.03046), TBD 2021 \
Yiding Zhang, Xiao Wang, Xunqiang Jiang, Chuan Shi, Yanfang Ye

1. [Hyperbolic attention networks](https://arxiv.org/abs/1805.09786), ICLR 2019 \
Caglar Gulcehre, Misha Denil, Mateusz Malinowski, Ali Razavi, Razvan Pascanu, Karl Moritz Hermann, Peter Battaglia, Victor Bapst, David Raposo, Adam Santoro, Nando de Freitas

1. [Coneheads: Hierarchy Aware Attention](https://arxiv.org/abs/2306.00392), NeurIPS 2023 \
Albert Tseng, Tao Yu, Toni J.B. Liu, Christopher De Sa

1. [Graph Geometry Interaction Learning](https://arxiv.org/abs/2010.12135), NeurIPS 2020 \
Shichao Zhu, Shirui Pan, Chuan Zhou, Jia Wu, Yanan Cao, Bin Wang

### [Emerging Hyperbolic Graph Learning Paradigms](#content)

**Diffusion-based Hyperbolic Representations**

1. [Hyperbolic Geometric Latent Diffusion Model for Graph Generation](https://arxiv.org/abs/2405.03188), ICML 2024 \
Xingcheng Fu, Yisen Gao, Yuecen Wei, Qingyun Sun, Hao Peng, Jianxin Li, Xianxian Li

1. [Hyperbolic Graph Diffusion Model](https://arxiv.org/abs/2306.07618), AAAI 2024 \
Lingfeng Wen, Xuan Tang, Mingjie Ouyang, Xiangxiang Shen, Jian Yang, Daxin Zhu, Mingsong Chen, Xian Wei

**Hyperbolic Graph Contrastive Learning**

1. [Enhancing Hyperbolic Graph Embeddings via Contrastive Learning](https://arxiv.org/abs/2201.08554), NeurIPS 2021 \
Jiahong Liu, Menglin Yang, Min Zhou, Shanshan Feng, Philippe Fournier-Viger

1. [Enhancing Hyperbolic Graph Embeddings via Contrastive Learning](https://openreview.net/forum?id=Iy0WQ0c75x), arXiv 2023 \
Yifei Zhang, Hao Zhu, Hao_Zhu, Jiahong Liu, Piotr Koniusz, Irwin King

## [Applications](#content)

### [Recommendation Systems](#content)

**Collaborative Filtering**
1. [HyperML: A Boosting Metric Learning Approach in Hyperbolic Space for Recommender Systems](https://dl.acm.org/doi/10.1145/3336191.3371850), WSDM 2020 \
Lucas Vinh Tran, Yi Tay, Shuai Zhang, Gao Cong, Xiaoli Li

1. [HGCF: Hyperbolic Graph Convolution Networks for Collaborative Filtering](https://dl.acm.org/doi/10.1145/3442381.3450101), WWW 2021 \
Jianing Sun, Zhaoyue Cheng, Saba Zuberi, Felipe Perez, Maksims Volkovs

1. [Fully Hyperbolic Graph Convolution Network for Recommendation](https://arxiv.org/abs/2108.04607), CIKM 2021 \
Liping Wang, Fenyu Hu, Shu Wu, Liang Wang

1. [Hyperbolic Diffusion Recommender Model](https://dl.acm.org/doi/10.1145/3696410.3714873), WWW 2025 \
Meng Yuan, Yutian Xiao, Wei Chen, Chou Zhao, Deqing Wang, Fuzhen Zhuang

1. [HRCF: Enhancing collaborative filtering via hyperbolic geometric regularization](https://arxiv.org/abs/2204.08176), WWW 2022 \
Menglin Yang, Min Zhou, Jiahong Liu, Defu Lian, Irwin King

1. [HICF: Hyperbolic Informative Collaborative Filtering](https://arxiv.org/abs/2207.09051), KDD 2022 \
Menglin Yang, Zhihao Li, Min Zhou, Jiahong Liu, Irwin King

1. [Hyperbolic Neural Collaborative Recommender](https://arxiv.org/abs/2104.07414), TKDE 2022 \
Anchen Li, Bo Yang, Hongxu Chen, Guandong Xu

1. [A Fashion Item Recommendation Model in Hyperbolic Space](https://arxiv.org/abs/2409.02599), CVPR 2024 \
Ryotaro Shimizu, Yu Wang, Masanari Kimura, Yuki Hirakawa, Takashi Wada, Yuki Saito, Julian McAuley

1. [Large Language Models Enhanced Hyperbolic Space Recommender Systems](https://arxiv.org/abs/2504.05694), SIGIR 2025 \
Wentao Cheng, Zhida Qin, Zexue Wu, Pengzhan Zhou, Tianyu Huang

**KG-enhanced Recommendation**
1. [Knowledge Based Hyperbolic Propagation](https://dl.acm.org/doi/10.1145/3404835.3462980), SIGIR 2021 \
Chang-You Tai, Chien-Kun Huang, Liang-Ying Huang, Lun-Wei Ku

1. [Modeling Scale-free Graphs with Hyperbolic Geometry for Knowledge-aware Recommendation](https://arxiv.org/abs/2108.06468), WSDM 2021 \
Yankai Chen, Menglin Yang, Yingxue Zhang, Mengchen Zhao, Ziqiao Meng, Jianye Hao, Irwin King

1. [HAKG: Hierarchy-Aware Knowledge Gated Network for Recommendation](https://arxiv.org/abs/2204.04959), SIGIR 2022 \
Yuntao Du, Xinjun Zhu, Lu Chen, Baihua Zheng, Yunjun Gao

1. [Lorentz Equivariant Model for Knowledge-Enhanced Hyperbolic Collaborative Filtering](https://arxiv.org/abs/2302.04545), KBS 2024 \
Bosong Huang, Weihao Yu, Ruzhong Xie, Jing Xiao, Jin Huang

1. [HGCH: A Hyperbolic Graph Convolution Network Model for Heterogeneous Collaborative Graph Recommendation](https://arxiv.org/abs/2304.02961), CIKM 2024 \
Lu Zhang, Ning Wu

**Social-aware Recommendation**
1. [HyperSoRec: Exploiting Hyperbolic User and Item Representations with Multiple Aspects for Social-aware Recommendation HyperSoRec](https://dl.acm.org/doi/fullHtml/10.1145/3463913), TOIS 2021 \
Hao Wang, Defu Lian, Hanghang Tong, Qi Liu

1. [HSR: Hyperbolic Social Recommender](https://arxiv.org/abs/2102.09389), Information Sciences 2022 \
Anchen Li, Bo Yang

1. [Hyperbolic Graph Learning for Social Recommendation](https://ieeexplore.ieee.org/document/10361607), TKDE 2023 \
Yonghui Yang, Le Wu, Kun Zhang, Richang Hong, Hailin Zhou, Zhiqiang Zhang

**Session-based Recommendation**
1. [HCGR: Hyperbolic Contrastive Graph Representation Learning for Session-based Recommendation](https://arxiv.org/abs/2107.05366), arXiv 2021 \
Naicheng Guo, Xiaolei Liu, Shaoshuai Li, Qiongxu Ma, Yunan Zhao, Bing Han, Lin Zheng, Kaixin Gao, Xiaobo Guo

1. [Hyperbolic Hypergraphs for Sequential Recommendation](https://arxiv.org/abs/2108.08134), CIKM 2022 \
Yicong Li, Hongxu Chen, Xiangguo Sun, Zhenchao Sun, Lin Li, Lizhen Cui, Philip S. Yu, Guandong Xu

1. [Enhancing Hierarchy-Aware Graph Networks with Deep Dual Clustering for Session-based Recommendation](https://dl.acm.org/doi/10.1145/3543507.3583247), WWW 2023 \
Jiajie Su, Chaochao Chen, Weiming Liu, Fei Wu

1. [Enhancing Session-Based Recommendation With Multi-Interest Hyperbolic Representation Networks](https://ieeexplore.ieee.org/document/10769057), IEEE TNNLS 2024 \
Tongcun Liu, Xukai Bao, Jiaxin Zhang, Kai Fang, Hailin Feng

1. [HMamba: Hyperbolic Mamba for Sequential Recommendation](https://arxiv.org/abs/2505.09205), arXiv 2025 \
Qianru Zhang, Honggang Wen, Wei Yuan, Crystal Chen, Menglin Yang, Siu-Ming Yiu, Hongzhi Yin

### [Knowledge Graph](#content)

**Geometric Transformation-based Methods**
1. [Multi-relational Poincaré Graph Embeddings](https://arxiv.org/abs/1905.09791), NeurIPS 2019 \
Ivana Balažević, Carl Allen, Timothy Hospedales

1. [Low-Dimensional Hyperbolic Knowledge Graph Embeddings](https://arxiv.org/abs/2005.00545), arXiv 2020 \
Ines Chami, Adva Wolf, Da-Cheng Juan, Frederic Sala, Sujith Ravi, Christopher Ré

1. [HyperKG: Hyperbolic Knowledge Graph Embeddings for Knowledge Base Completion](https://arxiv.org/abs/1908.04895), arXiv 2019 \
Prodromos Kolyvakis, Alexandros Kalousis, Dimitris Kiritsis

1. [Hyperbolic Hierarchy-Aware Knowledge Graph Embedding for Link Prediction](https://aclanthology.org/2021.findings-emnlp.251/), EMNLP 2021 \
Zhe Pan, Peng Wang

1. [Modeling Heterogeneous Hierarchies with Relation-specific Hyperbolic Cones](https://arxiv.org/abs/2110.14923), NeurIPS 2021 \
Yushi Bai, Rex Ying, Hongyu Ren, Jure Leskovec

1. [Geometry Interaction Knowledge Graph Embeddings](https://arxiv.org/abs/2206.12418), AAAI 2022 \
Zongsheng Cao, Qianqian Xu, Zhiyong Yang, Xiaochun Cao, Qingming Huang

1. [Enhancing hyperbolic knowledge graph embeddings via lorentz transformations](https://aclanthology.org/2024.findings-acl.272.pdf), ACL 2024 \
Xiran Fan, Minghua Xu, Huiyuan Chen, Yuzhong Chen, Mahashweta Das, Hao Yang

**GNN-based Methods**
1. [Knowledge association with hyperbolic knowledge graph embeddings](https://arxiv.org/abs/2010.02162), arXiv 2020 \
Zequn Sun, Muhao Chen, Wei Hu, Chengming Wang, Jian Dai, Wei Zhang

1. [Knowledge Graph Representation via Hierarchical Hyperbolic Neural Graph Embedding](https://ieeexplore.ieee.org/document/9671651), IEEE Big Data 2021 \
Shen Wang, Xiaokai Wei, Cicero Nogueira Dos Santos, Zhiguo Wang, Ramesh Nallapati, Andrew Arnold

1. [Mixed-Curvature Multi-Relational Graph Neural Network for Knowledge Graph Completion](https://dl.acm.org/doi/10.1145/3442381.3450118), WWW 2021 \
Shen Wang, Xiaokai Wei, Cicero Nogueira Nogueira dos Santos, Zhiguo Wang, Ramesh Nallapati, Andrew Arnold, Bing Xiang, Philip S. Yu, Isabel F. Cruz

1. [FFHR: Fully and Flexible Hyperbolic Representation for Knowledge Graph Completion](https://arxiv.org/abs/2302.04088), arXiv 2023 \
Wentao Shi, Junkang Wu, Xuezhi Cao, Jiawei Chen, Wenqiang Lei, Wei Wu, Xiangnan He

1. [Mixed Geometry Message and Trainable Convolutional Attention Network for Knowledge Graph Completion](https://ojs.aaai.org/index.php/AAAI/article/view/28745), AAAI 2024 \
Bin Shang, Yinliang Zhao, Jun Liu, Di Wang

### [Bioinformatics and Molecular Graphs](#content)

**Bioinformatics Graphs Representation**
1. [HiG2Vec: hierarchical representations of Gene Ontology and genes in the Poincaré ball](https://academic.oup.com/bioinformatics/article/37/18/2971/6184857?login=false), Bioinformatics 2021 \
Jaesik Kim, Dokyoon Kim, Kyung-Ah Sohn

1. [Hyperbolic relational graph convolution networks plus: a simple but highly efficient QSAR-modeling method](https://academic.oup.com/bib/article-abstract/22/5/bbab112/6235968?redirectedFrom=fulltext), Briefings in Bioinformatics 2021 \
Zhenxing Wu, Dejun Jiang, Chang-Yu Hsieh, Guangyong Chen, Ben Liao, Dongsheng Cao, Tingjun Hou

1. [Semi-supervised  hierarchical  drug  embedding  inhyperbolic space](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00681), J. Chem. Inf. Model 2020 \
Ke Yu\*, Shyam Visweswaran\*, and Kayhan Batmanghelich

1. [Deep generative model embedding of single-cell RNA-Seq profiles on hyperspheres and hyperbolic spaces](https://www.nature.com/articles/s41467-021-22851-4), Natur Communications 2021 \
   Jiarui Ding, Aviv Regev 

1. [Contrastive Poincaré Maps for single-cell data analysis](https://openreview.net/pdf?id=zsUKE98bNu), ICLR workshop 2024 \
   Nithya Bhasker, Hattie Chung, Louis Boucherie, Vladislav Kim, Stefanie Speidel, Melanie Weber

**Molecular Generation**
1. [Hyperbolic Geometric Latent Diffusion Model for Graph Generation](https://arxiv.org/abs/2405.03188), ICML 2024 \
   Xingcheng Fu, Yisen Gao, Yuecen Wei, Qingyun Sun, Hao Peng, Jianxin Li, Xianxian Li

1. [Hyperbolic Graph Diffusion Model](https://arxiv.org/abs/2306.07618), AAAI 2024 \
   Lingfeng Wen, Xuan Tang, Mingjie Ouyang, Xiangxiang Shen, Jian Yang, Daxin Zhu, Mingsong Chen, Xian Wei

1. [GGBall: Graph Generative Model on Poincaré Ball](https://www.arxiv.org/abs/2506.07198), arXiv 2025 \
Tianci Bu, Chuanrui Wang, Hao Ma, Haoren Zheng, Xin Lu, Tailin Wu

### [Other Application Scenarios](#content)

1. [Mix Dimension in Poincaré Geometry for 3D Skeleton-based Action Recognition](https://arxiv.org/abs/2007.15678), ACM MM 2020 \
Wei Peng, Jingang Shi, Zhaoqiang Xia, Guoying Zhao

1. [Exploring the scale-free nature of stock markets: Hyperbolic graph learning for algorithmic trading](https://dl.acm.org/doi/10.1145/3442381.3450095), WWW 2021 \
Ramit Sawhney, Shivam Agarwal, Arnav Wadhwa, Rajiv Shah
