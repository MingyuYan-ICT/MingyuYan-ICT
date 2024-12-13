---
layout: single
title: "Research Projects"
permalink: /research/
author_profile: true
---

### [Oct. 2018-Present] **Hardware Architecture for Graph Neural Network.**
- We first characterize the hybrid execution patterns of GCNs on Intel Xeon CPU. Guided by the characterization, we design a GCN accelerator, HyGCN, using a hybrid architecture to efficiently perform GCNs. In addition, we first identify the communication pattern and challenges of multi-node acceleration for GCNs on large-scale graphs. Guided by the above observations, we then propose MultiGCN, an efficient MultiAccSys for large-scale GCNs that trades network latency for network bandwidth. 
- [HyGCN: A GCN Accelerator with Hybrid Architecture](https://ieeexplore.ieee.org/abstract/document/9065592) (**HPCA'20**)
- [HiHGNN: Accelerating HGNNs through Parallelism and Data Reusability Exploitation](https://arxiv.org/pdf/2307.12765) （**IEEE TPDS 2024**）
- [GDR-HGNN: A Heterogeneous Graph Neural Networks Accelerator with Graph Decoupling and Recouping]() (**DAC'24**) 
- [Characterizing and Understanding HGNN Training on GPUs](https://dl.acm.org/doi/pdf/10.1145/3703356) (**ACM TACO 2024**)
- [Multi-Node Acceleration for Large-Scale GCNs](https://ieeexplore.ieee.org/abstract/document/9893364) (**IEEE TC 2022**)
- [Characterizing and Understanding GCNs on GPU](https://ieeexplore.ieee.org/abstract/document/8976117) (**IEEE CAL 2020**)


### [Jan. 2018-Present] **Hardware Architecture for Graph Processing.**
- To fully alleviate the irregularities at their origin---the data-dependent program behavior, we propose GraphDynS, a hardware/software co-design with decoupled datapath and data-aware dynamic scheduling. Aware of data dependencies extracted from the decoupled datapath, GraphDynS can elaborately schedule the program on-the-fly to maximize parallelism.
- [Alleviating Irregularity in Graph Analytics Acceleration: a Hardware/Software Co-Design Approach](https://dl.acm.org/doi/10.1145/3352460.3358318) (**MICRO'19**)
- [Alleviating Datapath Conflicts and Design Centralization in Graph Analytics Acceleration](https://dl.acm.org/doi/abs/10.1145/3489517.3530524) (**DAC'22**)


### [Oct. 2019-Present] **Algorithm/Software Optimization for Graph Neural Network.**
- We propose the Simple and Efficient Heterogeneous Graph Neural Network (SeHGNN), which reduces complexity by removing overused neighbor attention and avoiding repeated neighbor aggregation in every training epoch, and exhibits the characteristics of a simple network structure, high prediction accuracy, and fast training speed.
- [Simple and Efficient Heterogeneous Graph Neural Network](https://ojs.aaai.org/index.php/AAAI/article/view/26283) **(AAAI'23)**
- [A Comprehensive Survey on Distributed Training of Graph Neural Networks](https://ieeexplore.ieee.org/abstract/document/10348966/) **(PIEEE 2023)**
- [GNNSampler: Bridging the Gap between Sampling Algorithms of GNN and Hardware](https://link.springer.com/chapter/10.1007/978-3-031-26419-1_30) **(ECML-PKDD'22)**
- [Survey on Graph Neural Network Acceleration: An Algorithmic Perspective](https://arxiv.org/abs/2202.04822) **(IJCAI'22)**
- [DropNaE: Alleviating Irregularity for Large-scale Graph Representation Learning](https://papers.ssrn.com/sol3/Delivery.cfm?abstractid=4616038) (**Neural Networks 2024**)
- [fuseGNN: Accelerating Graph Convolutional Neural Network Training on GPGPU](https://dl.acm.org/doi/abs/10.1145/3400302.3415610) **(ICCAD'20)**
- [Sampling Methods for Efficient Training of Graph Convolutional Networks: A Survey](https://ieeexplore.ieee.org/abstract/document/9601152/) **(IEEE/CAA JAS 2022)**
  

### [Oct. 2021-Present] **Hardware Architecture for Heterogeneous Graph Neural Network.**
- We first quantitatively characterize a set of representative HGNN models on GPU to disclose the execution bound of each stage, inter-semantic-graph parallelism, and inter-semantic-graph data reusability in HGNNs. Guided by our findings, we propose a high-performance HGNN accelerator, HiHGNN, to alleviate the execution bound and exploit the newfound parallelism and data reusability in HGNNs. 
- [HiHGNN: Accelerating HGNNs through Parallelism and Data Reusability Exploitation](https://arxiv.org/abs/2307.12765) 
- [GDR-HGNN: A Heterogeneous Graph Neural Networks Accelerator with Graph Decoupling and Recouping] **(DAC'24)**.
- [Characterizing and Understanding HGNNs on GPUs](https://ieeexplore.ieee.org/abstract/document/9855397/) **(IEEE CAL 2022)**


### [Oct. 2022-Present] **Design Space Exploration Framework for CPU and Domain-specific Architecture.**
- To accelerate time-consuming multi-objective design space exploration of CPU microarchitecture, we investigate various prediction models and find out the most accurate basic model. We enhance the model by ensemble learning and generate Pareto-rank-based sample weights to improve prediction accuracy. A hypervolume-improvement-based optimization method to trade off between multiple objectives is proposed together with a uniformity-aware selection algorithm to jump out of the local optimum. Furthermore, the exploration time is reduced owing to a proposed Pareto-aware filter.
- [A High-accurate Multi-objective Exploration Framework for Design Space of CPU](https://ieeexplore.ieee.org/abstract/document/10247790/) **(DAC'23)**.
- [A Transfer Learning Framework for High-Accurate Cross-Workload Design Space Exploration of CPU](https://ieeexplore.ieee.org/abstract/document/10323840/) **(ICCAD'23)**
- [MoDSE: A High-Accurate Multi-Objective Design Space Exploration Framework for CPU Microarchitectures](https://ieeexplore.ieee.org/abstract/document/10345735) **(IEEE TCAD 2024)**







