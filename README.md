# Awesome Graph Neural Network Privacy Attack and Preservation Research Papers
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
![License](https://img.shields.io/github/license/NDS-VU/awesome-gnn-privacy-papers.svg?color=blue)⠀[![NDS-VU](https://img.shields.io/twitter/follow/nds_vu?style=social&logo=twitter)](https://twitter.com/intent/follow?screen_name=nds_vu)⠀

This repository aims to provide links to works about privacy attacks and privacy preservation on graph data with Graph Neural Networks (GNNs).

### Contents

* [1. Survey Papers](#1-survey-papers)
* [2. GNN Privacy Attack Papers](#2-gnn-privacy-attack-papers)
	* [2.1 Membership Inference Attack](#21-membership-inference-attack)
	* [2.2 Link Inference Attack](#22-link-inference-attack)
* [3. GNN Privacy Preservation Papers](#3-gnn-privacy-preservation-papers)
	* [3.1 Latent Factor Disentangling](#31-latent-factor-disentangling)
	* [3.2 Adversarial Training](#32-adversarial-training)
	* [3.3 Differentially Private Approaches](#33-differentially-private-approaches)
	* [3.4 Federated Learning](#34-federated-learning-approaches)

## 1. Survey Papers
1. **A Survey on Privacy in Graph Neural Networks: Attacks, Preservation, and Applications (coming soon!).**
   *authors from NDS Lab and ORNL.* 
1. **GNN Surveys (to be added).**
1. **Privacy in ML (to be added).**
 

## 2. GNN Privacy Attack Papers
### 2.1 Membership Inference Attack
1. **Membership Inference Attack on Graph Neural Networks.** *Iyiola E. Olatunji,Wolfgang Nejdl, and Megha Khosla.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2101.06570.pdf)
2. **Node-Level Membership Inference Attacks Against Graph Neural Networks.** *Xinlei He, Rui Wen, Yixin Wu, Michael Backes, Yun Shen, and Yang Zhang.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2102.05429.pdf)
3. **Quantifying Privacy Leakage in Graph Embedding.** *Vasisht Duddu, Antoine Boutet, and Virat Shejwalkar.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2010.00906.pdf)

### 2.2 Link Inference Attack
1. **Privacy Attacks on Network Embeddings.** *Michael Ellers, Michael Cochez, Tobias Schumacher, Markus Strohmaier, and Florian Lemmerich.* arXiv 2019. [[paper]](https://arxiv.org/pdf/1912.10979.pdf)[[code]](https://github.com/embedding-attack/embAttack)
2. **Stealing Links from Graph Neural Networks.** *Xinlei He, Jinyuan Jia, Michael Backes, Neil Zhenqiang Gong, and Yang Zhang.* USENIX Security 2021. [[paper]](https://www.usenix.org/system/files/sec21summer_he.pdf)
3. **Quantifying Privacy Leakage in Graph Embedding** *Vasisht Duddu, Antoine Boutet, and Virat Shejwalkar.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2010.00906.pdf)
4. **GraphMI: Extracting Private Graph Data from Graph Neural Networks.** *Zaixi Zhang, Qi Liu, Zhenya Huang, Hao Wang, Chengqiang Lu, Chuanren Liu, and Enhong Chen.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2106.02820.pdf)[[code]](https://github.com/zaixizhang/GraphMI)
5. **Inference Attacks Against Graph Neural Networks.** *Zhikun Zhang, Min Chen, Michael Backes, Yun Shen, and Yang Zhang.* USENIX Security 2022. [[paper]](https://arxiv.org/pdf/2110.02631.pdf)[[code]](https://github.com/Zhangzhk0819/GNN-Embedding-Leaks)

## 3. GNN Privacy Preservation Papers
### 3.1 Latent Factor Disentangling
1. **Adversarial Privacy Preserving Graph Embedding against Inference Attack.** *Kaiyang Li, Guangchun Luo, Yang Ye, Wei Li, Shihao Ji, and Zhipeng Cai.* IEEE IoT-J 2020. [[paper]](https://arxiv.org/pdf/2008.13072.pdf)[[code]](https://github.com/KaiyangLi1992/Privacy-Preserving-Social-Network-Embedding)

### 3.2 Adversarial Training
1. **Adversarial Privacy Preserving Graph Embedding against Inference Attack.** *Kaiyang Li, Guangchun Luo, Yang Ye, Wei Li, Shihao Ji, and Zhipeng Cai.* IEEE IoT-J 2020. [[paper]](https://arxiv.org/pdf/2008.13072.pdf)[[code]](https://github.com/KaiyangLi1992/Privacy-Preserving-Social-Network-Embedding)
2. **NetFense: Adversarial Defenses against Privacy Attacks on Neural Networks for Graph Data.** *I-Chung Hsieh and Cheng-Te Li.* IEEE-TKDE 2021. [[paper]](https://arxiv.org/pdf/2106.11865.pdf)[[code]](https://github.com/ICHproject/NetFense/)

### 3.3 Differentially Private Approaches
1. **Locally Private Graph Neural Networks.** *Sina Sajadmanesh and Daniel Gatica-Perez.* CCS 2021. [[paper]](https://arxiv.org/pdf/2006.05535.pdf)[[code]](https://github.com/sisaman/LPGNN)
2. **Releasing Graph Neural Networks with Differential Privacy Guarantees.** *Iyiola E. Olatunji, Thorben Funke, and Megha Khosla.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2109.08907.pdf)
3. **Graph Embedding for Recommendation against Attribute Inference Attacks.** *Shijie Zhang, Hongzhi Yin, Tong Chen, Zi Huang, Lizhen Cui, Xiangliang Zhang.* WWW 2021. [[paper]](https://arxiv.org/pdf/2101.12549.pdf)
4. **Information Obfuscation of Graph Neural Networks.** *Peiyuan Liao, Han Zhao, Keyulu Xu, Tommi Jaakkola, Geoffrey Gordon, Stefanie Jegelka, and Ruslan Salakhutdinov.* ICML 2021. [[paper]](http://proceedings.mlr.press/v139/liao21a/liao21a.pdf)[[code]](https://github.com/liaopeiyuan/GAL)

### 3.4 Federated Learning Approaches
1. **Vertically Federated Graph Neural Network for Privacy-Preserving Node Classification.** *Jun Zhou, Chaochao Chen, Longfei Zheng, Huiwen Wu, Jia Wu, Xiaolin Zheng, Bingzhe Wu, Ziqi Liu, and Li Wang.* arXiv 2020. [[paper]](https://arxiv.org/pdf/2005.11903.pdf)
2. **FedGNN: Federated Graph Neural Network for Privacy-Preserving Recommendation.** *Chuhan Wu, Fangzhao Wu, Yang Cao , Yongfeng Huang, and Xing Xie.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2102.04925.pdf)

**License**

- [CC0 Universal](https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/LICENSE)
