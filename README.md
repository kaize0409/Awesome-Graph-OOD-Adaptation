# Awesome-Graph-OOD-Adaptation

This repository contains a list of papers on graph out-of-distribution adaptation.

## Training-time Graph OOD Adaptation

### Model-centric Approaches

| Name  | Paper  | Code |
| :------------ |:---------------| :---------------| 
| **DAGNN**      | [[ICDM 2019] Domain-Adversarial Graph Neural Networks for Text Classification](https://shiruipan.github.io/publication/icdm-19-wu/icdm-19-wu.pdf) | [N/A] |
| **DANE**     |  [[ICJAI 2019] DANE: Domain Adaptive Network Embedding](https://arxiv.org/pdf/1906.00684.pdf)  |  [Unofficial](https://github.com/Jerry2398/DANE-Simple-implementation?tab=readme-ov-file) |
| **CDNE** |    [[TNNLS 2020] Network Together: Node Classification via Cross-Network Deep Network Embedding](https://arxiv.org/pdf/1901.07264.pdf)      |  [Code](https://github.com/shenxiaocam/CDNE) |
| **ACDNE** |   [[AAAI 2020] Adversarial Deep Network Embedding for Cross-network Node Classification](https://arxiv.org/pdf/2002.07366.pdf)  | [Code](https://github.com/shenxiaocam/ACDNE) |
| **UDA-GCN** |  [[TheWebConf 2020] Unsupervised Domain Adaptive Graph Convolutional Networks](https://shiruipan.github.io/publication/www-2020-wu/www-2020-wu.pdf)   | [Code](https://github.com/GRAND-Lab/UDAGCN) |
| **DGDA** |   [[TKDD 2024] Graph domain adaptation: A generative view.](https://arxiv.org/pdf/2106.07482.pdf)  |  [Code](https://github.com/rynewu224/GraphDA) |
| **SR-GNN** |  [[NeurIPS 2021] Shift-Robust GNNs: Overcoming the Limitations of Localized Graph Training Data](https://arxiv.org/pdf/2108.01099.pdf)  | [Code](https://github.com/GentleZhu/Shift-Robust-GNNs) |
| **ASN** | [ [CIKM 2021] Adversarial separation network for cross-network node classification](https://dl.acm.org/doi/abs/10.1145/3459637.3482228) | [Code](https://github.com/yuntaodu/ASN) |
| **AdaGCN** | [[TKDE 2022] Graph transfer learning via adversarial domain adaptation with graph convolution](https://arxiv.org/pdf/1909.01541.pdf) | [Code](https://github.com/daiquanyu/AdaGCN_TKDE) |
| **GraphAE** | [[TKDE 2023] Learning adaptive node embeddings across graphs](https://ieeexplore.ieee.org/document/9737419) |  [N/A] |
| **GRADE** | [ [AAAI 2023] Non-iid transfer learning on graphs](https://arxiv.org/pdf/2212.08174.pdf)| [Code](https://github.com/jwu4sml/GRADE) | 
| **JHGDA** | [ [CIKM 2023] Improving graph domain adaptation with network hierarchy](https://dl.acm.org/doi/pdf/10.1145/3583780.3614928) | [Code](https://github.com/Skyorca/JHGDA) |
| **SGDA** | [ [ICJAI 2023] Semi-supervised Domain Adaptation in Graph Transfer Learning](https://www.ijcai.org/proceedings/2023/0253.pdf) | [Code](https://github.com/joe817/SGDA) |
| **SRNC** | [ [NeurIPS 2022] Shift-Robust Node Classification via Graph Clustering Co-training](https://www.cs.emory.edu/~jyang71/files/srnc.pdf) | [N/A] |
| **StruRW** | [[ICML 2023] Structural re-weighting improves graph domain adaptation](https://arxiv.org/pdf/2306.03221.pdf) | [Code](https://github.com/Graph-COM/StruRW)
| **GCONDA++** | [[arXiv] Explaining and Adapting Graph Conditional Shift](https://arxiv.org/pdf/2306.03256.pdf) | [N/A] |
| **KDGA** | [[NeurIPS 2022] Knowledge distillation improves graph structure augmentation for graph neural networks](https://openreview.net/pdf?id=7yHte3tH8Xh) | [Code](https://github.com/LirongWu/KDGA)
| **SS/MFR-Reg** | [[ICLR 2023] Graph domain adaptation via theory-grounded spectral regularization](https://openreview.net/pdf?id=OysfLgrk8mk) | [Code](https://github.com/Shen-Lab/GDA-SpecReg) |
| **KTGNN** | [[TheWebConf 2023] Predicting the Silent Majority on Graphs: Knowledge Transferable Graph Neural Network](https://arxiv.org/pdf/2302.00873.pdf) | [Code](https://github.com/wendongbi/KT-GNN)

### Data-centric Approaches

| Name  | Paper  | Code |
| :------------ |:---------------| :---------------| 
| **IW** | [[TheWebConf 2013] Predicting positive and negative links in signed social networks by transfer learning](https://dl.acm.org/doi/abs/10.1145/2488388.2488517) | [N/A] |
| **NES-TL** | [[TNSE 2020] Nes-tl: Network embedding similarity-based transfer learning](http://www.xuanqi-net.com/Papers/TNSE19-NES.pdf)| [N/A] |
| **RSS-GNN** | [[BIBM 2022] Reinforced Sample Selection for Graph Neural Networks Transfer Learning](https://ieeexplore.ieee.org/document/9995652) | [N/A] |
| **DR-GST** | [[TheWebConf 2022] Confidence may cheat: Self-training on graph neural networks under distribution shift](https://arxiv.org/pdf/2201.11349.pdf) | [Code](https://github.com/bupt-gamma/dr-gst) |
| **FakeEdge** | [[LoG 2022] Fakeedge: Alleviate dataset shift in link prediction](https://arxiv.org/pdf/2211.15899.pdf) | [Code](https://github.com/Barcavin/FakeEdge)
| **Bridged-GNN** | [[CIKM 2023] Bridged-GNN: Knowledge Bridge Learning for Effective Knowledge Transfer](https://arxiv.org/pdf/2308.09499v1.pdf) | [Code](https://github.com/wendongbi/Bridged-GNN)
| **DC-GST** | [[WSDM 2024] Distribution consistency based self-training for graph neural networks with sparse labels](https://arxiv.org/pdf/2401.10394.pdf) | [N/A] |


## Test-time Graph OOD Adaptation


### Model-centric Approaches


| Name  | Paper  | Code |
| :------------ |:---------------| :---------------| 
| **GraphControl**  |  [[arXiv] GraphControl: Adding Conditional Control to Universal Graph Pre-trained Models for Graph Domain Transfer Learning](https://arxiv.org/pdf/2310.07365.pdf)    | [N/A] |
| **SOGA** |  [[WSDM 2024] Source free unsupervised graph domain adaptation](https://arxiv.org/pdf/2112.00955.pdf)      |  [Code](https://github.com/HaitaoMao/SOGA) |
| **GT3** |  [[arXiv] Test-time training for graph neural networks](https://arxiv.org/pdf/2210.08813.pdf)       |   [N/A] |
| **GAPGC** |  [[ICML 2022] GraphTTA: Test Time Adaptation on Graph Neural Networks](https://arxiv.org/pdf/2208.09126.pdf)    | [N/A] |
| **GraphGLOW** |  [[KDD 2023] GraphGLOW: Universal and Generalizable Structure Learning for Graph Neural Networks](https://arxiv.org/pdf/2306.11264.pdf)  | [Code](https://github.com/WtaoZhao/GraphGLOW)

### Data-centric Approaches

| Name  | Paper  | Code |
| :------------ |:---------------| :---------------| 
| **FRGNN** |  [[arXiv] FRGNN: Mitigating the Impact of Distribution Shift on Graph Neural Networks via Test-Time Feature Reconstruction](https://arxiv.org/pdf/2308.09259.pdf)   | [N/A] |
| **GTRANS** | [[ICLR 2023] Empowering graph representation learning with test-time graph transformation](https://openreview.net/pdf?id=Lnxl5pr018)    | [Code](https://github.com/ChandlerBang/GTrans)


## Related: Transferability evaluation 

| Name  | Paper  | Code |
| :------------ |:---------------| :---------------| 
| **EGI** |  [[NeurIPS 2021] Transfer Learning of Graph Neural Networks with Ego-graph Information Maximization](https://proceedings.neurips.cc/paper/2021/file/0dd6049f5fa537d41753be6d37859430-Paper.pdf) | [Code](https://github.com/GentleZhu/EGI) |
| **WNN** | [[NeurIPS 2020] Graphon Neural Networks and the Transferability of Graph Neural Networks](https://arxiv.org/pdf/2006.03548.pdf) | [N/A] |
| **TMD** | [[NeurIPS 2022] Tree Mover’s Distance: Bridging Graph Metrics and Stability of Graph Neural Networks](https://arxiv.org/pdf/2210.01906.pdf) | [Code](https://github.com/chingyaoc/TMD) |
|**W2PGNN** | [[KDD 2023] When to Pre-Train Graph Neural Networks? From Data Generation Perspective!](https://arxiv.org/pdf/2303.16458.pdf)| [Code](https://github.com/caoyxuan/W2PGNN) |





