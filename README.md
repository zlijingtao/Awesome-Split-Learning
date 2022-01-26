# Awesome-Split-Learning    [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A incomplete survey for Split Learning (comprehensive enough) and Federated Learning (only most representative works).

This list covers most Split Learning works. We also include some Federated Learning works for a easy comparison with SL - are just a sub-list of https://github.com/chaoyanghe/Awesome-Federated-Learning.

*** Updated at 2022/1/26 ***

## Category
- ### [Split Learning Schemes](#split-learning-schemes-1)
    - #### Sequentual/Original Split Learning
    - #### Split Federated Learning
    - #### Parallel Split Learning
    - #### Two-party Split Learning

- ### [Evaluation Work](#evaluation-work-1)

- ### [Communication Reduction](#communication-reduction-1)

- ### [Input Leakage](#input-leakage-1)
    - #### HBC Server
    - #### Malicious Server
- ### [Input Leakage Mitigation](#input-leakage-mitigation-1)
    - #### HBC Server
    - #### Malicious Server


*** Updated at 2022/1/26 ***

# Split Learning

<h2 id="#split-learning-schemes">Split Learning Schemes</h2>

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

4. [Efficient Privacy Preserving Edge Intelligent Computing Framework for Image Classification in IoT](https://ieeexplore.ieee.org/abstract/document/9576096)

5. [Flexible Parallel Learning in Edge Scenarios: Communication, Computational and Energy Cost](https://arxiv.org/abs/2201.07402)

6. [Splitfed learning without client-side synchronization: Analyzing client-side split network portion size to overall performance](https://arxiv.org/abs/2109.09246)
### Two-party Split Learning

1. (ICLR '21 workshop) [Pyvertical: A vertical federated learning framework for multi-headed splitnn](https://arxiv.org/abs/2104.00489)

2. (ICLR '22) [Label Leakage and Protection in Two-party Split Learning](https://arxiv.org/abs/2102.08504)

3. [Gradient Inversion Attack: Leaking Private Labels in Two-Party Split Learning](https://arxiv.org/abs/2112.01299)

4. [FedV: Privacy-Preserving Federated Learning over Vertically Partitioned Data](https://arxiv.org/abs/2103.03918)

### Other Split Learning Variants

1. (NeurIPS '20) [Group knowledge transfer: Federated learning of large cnns at the edge](https://arxiv.org/abs/2007.14513)

<h2 id="#evaluation-work">Evaluation Work</h2>

1. [End-to-End Evaluation of Federated Learning and Split Learning for Internet of Things](https://arxiv.org/abs/2003.13376)

2. [Detailed comparison of communication efficiency of split learning and federated learning](https://arxiv.org/abs/1909.09145)

3. [Advancements of Federated Learning Towards Privacy Preservation: From Federated Learning to Split Learning](https://link.springer.com/chapter/10.1007/978-3-030-70604-3_4)

4. [Triad of Split Learning: Privacy, Accuracy, and Performance](https://ieeexplore.ieee.org/abstract/document/9620846)

5. [Computational Privacy with Split Learning: Benchmarking of Algorithmic Defenses against Reconstruction Attacks](https://dspace.mit.edu/handle/1721.1/139497)

<h2 id="#communication-reduction">Communication Reduction</h2>

1. [Communication and Computation Reduction for Split Learning using Asynchronous Training](https://ieeexplore.ieee.org/abstract/document/9605049)

2. [Communication-Efficient Multimodal Split Learning for mmWave Received Power Prediction](https://ieeexplore.ieee.org/abstract/document/9026781?)

3. [Communication-Efficient Split Learning Based on Analog Communication and Over the Air Aggregation](https://arxiv.org/abs/2106.00999)

4. [A Federated Learning Framework for Healthcare IoT devices](https://arxiv.org/abs/2005.05083)

<h2 id="#input-leakge">Input Leakage</h2>

### HBC Server

1. (CCS '15) [Model Inversion Attacks that Exploit Confidence Information and Basic Countermeasures](https://dl.acm.org/doi/abs/10.1145/2810103.2813677)

2. (Asia-CCS '20) [Can We Use Split Learning on 1D CNN Models for Privacy Preserving Training?](https://dl.acm.org/doi/abs/10.1145/3320269.3384740?)


3. (ACSAC '19) [Model inversion attacks against collaborative inference](https://dl.acm.org/doi/abs/10.1145/3359789.3359824?)

4. [UnSplit: Data-Oblivious Model Inversion, Model Stealing, and Label Inference Attacks Against Split Learning](https://arxiv.org/abs/2108.09033)

### Malicious Server

1. (CCS '21) [Unleashing the Tiger: Inference Attacks on Split Learning](https://dl.acm.org/doi/abs/10.1145/3460120.3485259?)

2. (AAAI workshop) [Feature Space Hijacking Attacks against Differentially Private Split Learning](https://arxiv.org/abs/2201.04018?context=cs.AI)

<h2 id="#input-leakge-mitigation">Input Leakage Mitigation</h2>

### HBC Server

1. (Asia-CCS '20, increasing depth and differential privacy) [Can We Use Split Learning on 1D CNN Models for Privacy Preserving Training?](https://dl.acm.org/doi/abs/10.1145/3320269.3384740?)

2. [NoPeek: Information leakage reduction to share activations in distributed deep learning](https://ieeexplore.ieee.org/abstract/document/9346367?)

3. [NoPeek-Infer: Preventing face reconstruction attacks in distributed inference after on-premise training](https://ieeexplore.ieee.org/abstract/document/9667085)

4. [Practical Defences Against Model Inversion Attacks for Split Neural Networks](https://arxiv.org/abs/2104.05743)

5. [Get your Foes Fooled: Proximal Gradient Split Learning for Defense against Model Inversion Attacks on IoMT data](https://arxiv.org/abs/2201.04569)

### Malicious Server

1. [SplitGuard: Detecting and Mitigating Training-Hijacking Attacks in Split Learning](https://arxiv.org/abs/2108.09052)

<h2 id="#other-application">Other Applications</h2>

### Hardware Demo

1. [SplitEasy: A Practical Approach for Training ML models on Mobile Devices](https://dl.acm.org/doi/abs/10.1145/3446382.3448362)

2. [Split learning on FPGAs](https://dspace.mit.edu/handle/1721.1/129125)

### Heterogeneous SL

1. [FedAdapt: Adaptive Offloading for IoT Devices in Federated Learning](https://arxiv.org/abs/2107.04271)

2. [AdaSplit: Adaptive Trade-offs for Resource-constrained Distributed Deep Learning](https://arxiv.org/abs/2112.01637)

### Non-i.i.d. SL

1. [Handling Data Heterogeneity with Generative Replay in Collaborative Learning for Medical Imaging](https://arxiv.org/abs/2106.13208)

### Multi-Task SL

2. (NeurIPS '21) [Federated Split Task-Agnostic Vision Transformer for COVID-19 CXR Diagnosis](https://proceedings.neurips.cc/paper/2021/hash/ceb0595112db2513b9325a85761b7310-Abstract.html)

### Device Mobility

1. [FedFly: Towards Migration in Edge-based Distributed Federated Learning](https://arxiv.org/abs/2111.01516)

### Binarization SL

1.[Efficient binarizing split learning based deep models for mobile applications](https://aip.scitation.org/doi/abs/10.1063/5.0066470)

### Split Learning + HE/MPC

1. [PrivColl: Practical Privacy-Preserving Collaborative Machine Learning](https://link.springer.com/chapter/10.1007/978-3-030-58951-6_20)

### Heteromodel SL

1. [Distributed Heteromodal Split Learning for Vision Aided mmWave Received Power Prediction](https://arxiv.org/abs/2007.08208)

### RNN SL

1. [FedSL: Federated Split Learning on Distributed Sequential Data in Recurrent Neural Networks](https://arxiv.org/abs/2011.03180)

### Graph NN + SL

1. [Towards Representation Identical Privacy-Preserving Graph Neural Network via Split Learning](https://arxiv.org/abs/2107.05917)

# Federated Learning

## Feature Inference Attack

1. [Deep Models Under the GAN: Information Leakage from Collaborative Deep Learning](https://arxiv.org/abs/1702.07464)

2. [Beyond Inferring Class Representatives: User-Level Privacy Leakage From Federated Learning](https://arxiv.org/abs/1812.00535)

## Inversion Attack

1. [Inverting Gradients -- How easy is it to break privacy in federated learning?](https://arxiv.org/abs/2003.14053)

2. [Deep Leakage from Gradients](https://link.springer.com/chapter/10.1007/978-3-030-63076-8_2)

3. [See Through Gradients: Image Batch Recovery via GradInversion](https://openaccess.thecvf.com/content/CVPR2021/html/Yin_See_Through_Gradients_Image_Batch_Recovery_via_GradInversion_CVPR_2021_paper.html)

4. [Gradient Inversion with Generative Image Prior](https://proceedings.neurips.cc/paper/2021/hash/fa84632d742f2729dc32ce8cb5d49733-Abstract.html)

## Inversion Attack Mitigation

1. [Soteria: Provable Defense Against Privacy Leakage in Federated Learning From Representation Perspective](https://openaccess.thecvf.com/content/CVPR2021/html/Sun_Soteria_Provable_Defense_Against_Privacy_Leakage_in_Federated_Learning_From_CVPR_2021_paper.html)
