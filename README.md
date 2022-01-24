# Awesome-Split-Learning
A incomplete survey for Split Learning (comprehensive enough) and Federated Learning (only most representative works).

This list covers most Split Learning works. We also include some Federated Learning works for a easy comparison with SL - are just a sub-list of https://github.com/chaoyanghe/Awesome-Federated-Learning.

*** Updated at 2022/1/23 ***

## Category
- ### [Split Learning Schemes](#split-learning-schemes)
    - #### Sequentual/Original Split Learning
    - #### Split Federated Learning
    - #### Parallel Split Learning
    - #### Two-party Split Learning

- ### [Evaluation Work](#evaluation-work)

- ### [Communication Reduction](#communication-reduction)

- ### [Input Leakage](#input-leakage)
    - #### HBC Server
    - #### Malicious Server
- ### [Input Leakage Mitigation](#input-leakage-mitigation)
    - #### HBC Server
    - #### Malicious Server


*** Updated at 2022/1/23 ***

## [Split Learning Schemes](#split-learning-schemes)

### Sequential Split Learning (Original)
1. [Distributed learning of deep neural network over multiple agents](https://www.sciencedirect.com/science/article/abs/pii/S1084804518301590?via%3Dihub)

2. [Split learning for health: Distributed deep learning
without sharing raw patient data](https://arxiv.org/pdf/1812.00564.pdf)

3. [Split Learning for collaborative deep learning in healthcare](https://arxiv.org/pdf/1912.12115.pdf)

### Split Federated Learning
1. [SplitFed: When Federated Learning Meets Split Learning](https://arxiv.org/abs/2004.12088)

2. (NeurIPS '21) [Federated Split Task-Agnostic Vision Transformer for COVID-19 CXR Diagnosis](https://proceedings.neurips.cc/paper/2021/hash/ceb0595112db2513b9325a85761b7310-Abstract.html)

3. [Combining split and federated architectures for efficiency and privacy in deep learning](https://dl.acm.org/doi/abs/10.1145/3386367.3431678?)

4. [Privacy-Sensitive Parallel Split Learning](https://ieeexplore.ieee.org/abstract/document/9016486?)

### Parallel Split Learning (SFL without "F")

1. [Comparison of Privacy-Preserving Distributed Deep Learning Methods in Healthcare](https://arxiv.org/abs/2012.12591)

2. [Spatio-Temporal Split Learning](https://ieeexplore.ieee.org/abstract/document/9525563)

3. [Server-Side Local Gradient Averaging and Learning Rate Acceleration for Scalable Split Learning](https://arxiv.org/abs/2112.05929)

### Two-party Split Learning

1. (ICLR '22) [Label Leakage and Protection in Two-party Split Learning](https://arxiv.org/abs/2102.08504)

2. [Gradient Inversion Attack: Leaking Private Labels in Two-Party Split Learning](https://arxiv.org/abs/2112.01299)

## [Evaluation Work](#evaluation-work)

1. [End-to-End Evaluation of Federated Learning and Split Learning for Internet of Things](https://arxiv.org/abs/2003.13376)

2. [Detailed comparison of communication efficiency of split learning and federated learning](https://arxiv.org/abs/1909.09145)

3. [Advancements of Federated Learning Towards Privacy Preservation: From Federated Learning to Split Learning](https://link.springer.com/chapter/10.1007/978-3-030-70604-3_4)

## [Communication Reduction](#communication-reduction)

1. [Communication-Efficient Multimodal Split Learning for mmWave Received Power Prediction](https://ieeexplore.ieee.org/abstract/document/9026781?)

## [Input Leakge](#input-leakge)

### HBC Server
1. (CCS '15) [Model Inversion Attacks that Exploit Confidence Information and Basic Countermeasures](https://dl.acm.org/doi/abs/10.1145/2810103.2813677)

2. (Asia-CCS '20) [Can We Use Split Learning on 1D CNN Models for Privacy Preserving Training?](https://dl.acm.org/doi/abs/10.1145/3320269.3384740?)


3. (ACSAC '19) [Model inversion attacks against collaborative inference](https://dl.acm.org/doi/abs/10.1145/3359789.3359824?)

4. [UnSplit: Data-Oblivious Model Inversion, Model Stealing, and Label Inference Attacks Against Split Learning](https://arxiv.org/abs/2108.09033)

### Malicious Server

1. (CCS '21) [Unleashing the Tiger: Inference Attacks on Split Learning](https://dl.acm.org/doi/abs/10.1145/3460120.3485259?)

## [Input Leakge Mitigation](#input-leakge-mitigation)

### HBC Server

1. (Asia-CCS '20, increasing depth and differential privacy) [Can We Use Split Learning on 1D CNN Models for Privacy Preserving Training?](https://dl.acm.org/doi/abs/10.1145/3320269.3384740?)

2. [NoPeek: Information leakage reduction to share activations in distributed deep learning](https://ieeexplore.ieee.org/abstract/document/9346367?)

### Malicious Server
1. [SplitGuard: Detecting and Mitigating Training-Hijacking Attacks in Split Learning](https://arxiv.org/abs/2108.09052)
