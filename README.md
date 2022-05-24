# Awesome DL Scheduling Papers

## Schedulers for DL training

| **Scheduler** | **Year** | **Series** | **Paper** | **Objective** | **Algorithms** | **Heterogenous** | **Elastic** | **AutoML** | **Source Code** |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Synergy | 2022 | OSDI | [Paper](https://arxiv.org/abs/2110.06073) | ♣  | Optimistic profiling; Greedy   scheduling | - | - | - | - |
| Singularity | 2022 | arxiv | [Paper](https://arxiv.org/abs/2202.07848) | ✿♣♦ | Device Proxy; Replica splicing; etc | - | ✔ | - | - |
| GADGET | 2022 | INFOCOM | [Paper](https://arxiv.org/abs/2202.01158) | ✿♣ | Greedy; G-VNE | - | ✔ | - | [Code](https://zenodo.org/record/5847644#.YishWH8zZhE) |
| EDL | 2022 | TPDS | [Paper](https://ieeexplore.ieee.org/document/9373916) | ✿♣ | Stop-free scaling; Graceful exit;etc | - | ✔ | - | - |
| Aryl | 2022 | arxiv | [Paper](https://arxiv.org/abs/2202.07896) | ✿♣ | Capacity Loaning | - | ✔ | ✔ | - |
| AOnline | 2022 | TCC | [Paper](https://ieeexplore.ieee.org/document/9682563) | ✿♣ | Integer Linear Programming | - | ✔ | - | - |
| Ali-MLaaS | 2022 | NSDI | [Paper](https://www.usenix.org/conference/nsdi22/presentation/weng) | ✿♣ | GPU Sharing; Predictable Duration | - | - | - | [Code](https://github.com/alibaba/clusterdata/tree/master/cluster-trace-gpu-v2020) |
| SMD | 2021 | INFOCOM | [Paper](https://arxiv.org/abs/2105.13855) | ♣ | Multi-dimensional-knapsack Decomposition | - | - | - | - |
| SEER | 2021 | SoCC | [Paper](https://dl.acm.org/doi/pdf/10.1145/3472883.3486989) | ▲ | Dynamic Resource Allocation | - | ✔ | ✔ | - |
| RubberBand | 2021 | EuroSys | [Paper](https://dl.acm.org/doi/10.1145/3447786.3456245) |  ♦ | Model JCT and Cost Prior to Runtime | - | ✔ | ✔ | - |
| POP | 2021 | SOSP | [Paper](https://dl.acm.org/doi/10.1145/3477132.3483588) | ♥♣ | Partitioned Optimization | ✔ | - | - | [Code](https://github.com/stanford-futuredata/POP) |
| Pollux | 2021 | OSDI | [Paper](https://www.usenix.org/conference/osdi21/presentation/qiao) | ✿♣♥ | Goodput; Dynamic batch size and learning rate | - | ✔ | ✔ | [Code](https://github.com/petuum/adaptdl) |
| ONES | 2021 | SC | [Paper](https://dl.acm.org/doi/10.1145/3458817.3480859) | ✿♣ | Online evolutionary search | - | ✔ | - | [Code](https://github.com/kurisusnowdeng/ones_sc21) |
| Liquid | 2021 | TPDS | [Paper](https://ieeexplore.ieee.org/document/9664375) | ♣  | Random forest; Best-fit; Grouping genetic | - | - | - | [Code](https://github.com/PasaLab/Liquid) |
| Jigsaw | 2021 | DistributedML | [Paper](https://dl.acm.org/doi/10.1145/3488659.3493778) | ♣ | Structured Partial Training | - | - | - | - |
| Horus | 2021 | TPDS | [Paper](https://ieeexplore.ieee.org/document/9428512) | ✿♣ | XGBoost-based interference prediction | - | - | - | - |
| Hermes | 2021 | Electronics | [Paper](https://www.mdpi.com/2079-9292/10/3/350) | ♣ |  Time-sharing Execution   with Low Overhead | - | - | ✔ | - |
| Helios | 2021 | SC | [Paper](https://dl.acm.org/doi/abs/10.1145/3458817.3476223) | ♣♦ | Data Driven Prediction; QSSF; CES | - | - | - | [Code](https://github.com/S-Lab-System-Group/HeliosArtifact) |
| DynamoML | 2021 | CLOSER | [Paper](https://www.scitepress.org/Papers/2021/104834/104834.pdf) | ✿♣ | Combine KubeShare and Dragon | - | ✔ | - | - |
| Chronus | 2021 | SoCC | [Paper](https://dl.acm.org/doi/abs/10.1145/3472883.3486978) | ♠ | Linear Programming; Local Search Allocation | - | - | - | [Code](https://github.com/S-Lab-System-Group/ChronusArtifact/) |
| Astraea | 2021 | TPDS | [Paper](https://ieeexplore.ieee.org/document/9655467/) | ♥ | Long-Term GPU-time Fairness | - | - | - | [Code](https://github.com/yzs981130/Astraea_Artifacts) |
| ANDREAS | 2021 | FCloud | [Paper](https://arxiv.org/abs/2105.05080) | ♦ | Randomized Greedy Algorithm | - | - | - | - |
| AFS | 2021 | NSDI | [Paper](https://www.usenix.org/conference/nsdi21/presentation/hwang) | ✿♣ | Apathetic Future Share; CoDDL | - | ✔ | - | - |
| $DL^2$ | 2021 | TPDS | [Paper](https://arxiv.org/abs/1909.06040) | ♣ | RL Scheduler | - | ✔ | - | [Code](https://github.com/pengyanghua/DL2) |
| Yeung | 2020 | HotCloud | [Paper](https://www.usenix.org/conference/hotcloud20/presentation/yeung) | ✿ | GPU Utilization Prediction  | - | - | - | - |
| Vaibhav et al. | 2020 | MASCOTS | [Paper](https://ieeexplore.ieee.org/abstract/document/9285954) | ✿♣ | Dynamic programming optimization | - | ✔ | - | - |
| Themis | 2020 | NSDI | [Paper](https://www.usenix.org/conference/nsdi20/presentation/mahajan) | ♥ | Finish-Time Fairness; Auction Bid | - | - | - | - |
| SPIN | 2020 | INFOCOM | [Paper](https://ieeexplore.ieee.org/document/9155445/) | ♣ | Rounding-based Randomized Approximation | - | - | - | - |
| Salus | 2020 | MLSys | [Paper](https://proceedings.mlsys.org/paper/2020/hash/f7177163c833dff4b38fc8d2872f1ec6-Abstract.html) | ✿♣ | Fast job switching; Memory sharing | - | - | - | [Code](https://github.com/SymbioticLab/Salus) |
| Parrot | 2020 | TCC | [Paper](https://ieeexplore.ieee.org/document/9269382) | ♣ | Linear Programming | - | - | - | - |
| Non-Intrusive | 2020 | SC | [Paper](https://dl.acm.org/doi/abs/10.5555/3433701.3433820) | ✿♣ | SideCar; Early initialization | - | ✔ | - | - |
| MLFS | 2020 | CoNext | [Paper](https://dl.acm.org/doi/10.1145/3386367.3432588) | ♣♠ | RL Scheduler | - | - | - | [Code](https://github.com/hiddenlayer2020/ML-Job-Scheduler-MLFS) |
| MLCloudPrice | 2020 | DISPA | [Paper](https://cs.stanford.edu/~matei/papers/2020/dispa_cloud_ml.pdf) |  ♣♦ | Linear programming; Spot-Instance Training | - | - | - | [Code](https://github.com/stanford-futuredata/training_on_a_dime) |
| MARBLE | 2020 | CCGRID | [Paper](https://ieeexplore.ieee.org/document/9407835) | ✿♣ | Offline profiling based scaling | - | ✔ | - | - |
| HiveD | 2020 | OSDI | [Paper](https://www.usenix.org/conference/osdi20/presentation/zhao-hanyu) | ♣ | Buddy Cell Allocation | - | - | - | [Code](https://github.com/microsoft/hivedscheduler) |
| GENIE | 2020 | TPDS | [Paper](https://ieeexplore.ieee.org/document/8778770) | ♠ | Light Profiler | - | ✔ | - | - |
| Gavel | 2020 | OSDI | [Paper](https://www.usenix.org/conference/osdi20/presentation/narayanan-deepak) | ♣♥ | Linear programming; Round-based   scheduling | ✔ | - | - | [Code](https://github.com/stanford-futuredata/gavel) |
| E-LAS | 2020 | ICPP | [Paper](https://dl.acm.org/doi/fullHtml/10.1145/3404397.3404415) | ♣ | Real-time Epoch Progress Rate; LAS | - | - | - | - |
| Elan | 2020 | ICDCS | [Paper](https://ieeexplore.ieee.org/document/9355755) | ✿♣ | Hybrid scaling; IO-free replication;etc | - | ✔ | - | - |
| Co-scheML | 2020 | ACSOS | [Paper](https://ieeexplore.ieee.org/document/9196380) | ♣ | Interference-Aware Scheduler; Random Forest | - | - | - | - |
| CODA | 2020 | ICDCS | [Paper](https://ieeexplore.ieee.org/document/9355823) | ♣ | Adaptive CPU allocator; Contention eliminator; etc | ✔* | - | - | - |
| Antman | 2020 | OSDI | [Paper](https://www.usenix.org/system/files/osdi20-xiao.pdf) | ✿♣ | Framework-Cluster Co-Design | - | ✔ | - | [Code](https://github.com/alibaba/GPU-scheduler-for-deep-learning) |
| Ada-SRSF | 2020 | arxiv | [Paper](https://arxiv.org/abs/2002.10105) | ♣ | AdaDUAL; Least workload first | ✔* | - | - | - |
| $Gandiva_{fair}$ | 2020 | EuroSys | [Paper](https://dl.acm.org/doi/abs/10.1145/3342195.3387555) | ♥♣ | Gang-Aware Lottery; Automatic   Trading | ✔ | - | - | - |
| Tiresias | 2019 | NSDI | [Paper](https://www.usenix.org/conference/nsdi19/presentation/gu) | ♣ | Gittins index;  Least-Attained Service (LAS) | - | - | - | [Code](https://github.com/SymbioticLab/Tiresias) |
| Philly | 2019 | ATC | [Paper](https://www.usenix.org/conference/atc19/presentation/jeon) | ♣ | Locality-Relaxity | - | - | - | [Code](https://github.com/msr-fiddle/philly-traces) |
| JPAS | 2019 | JNCA | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1084804520300643) | ♣▲ | Accuracy Curve Modelling | - | - | ✔ | - |
| Jahani | 2019 | ICCCS | [Paper](https://ieeexplore.ieee.org/document/8888151) | ♦ | Linear Programming | ✔ | ✔ | - | - |
| HyperSched | 2019 | SoCC | [Paper](https://dl.acm.org/doi/10.1145/3357223.3362719) | ♠ ▲ | ASHA; Dynamic Resource   Allocation | - | ✔ | ✔ | - |
| Harmony | 2019 | INFOCOM | [Paper](https://ieeexplore.ieee.org/document/8737460) | ♣ | RL Scheduler; Bin Packing | - | - | - | - |
| FfDL | 2019 | Middleware | [Paper](https://dl.acm.org/doi/10.1145/3361525.3361538) | ♣ | Lesson-motivated Design | - | - | - | [Code](https://github.com/IBM/FfDL) |
| Dragon | 2019 | CLOSER | [Paper](https://pdfs.semanticscholar.org/3075/cf85b9a70092bcafa10757c6ee6f73b75c2e.pdf) | ✿♣ | GPU time-sharing; Autoscaling | - | ✔ | - | - |
| Cynthia | 2019 | ICPP | [Paper](https://dl.acm.org/doi/10.1145/3337821.3337873) | ♦ | Performance Modelling | - | ✔ | - | - |
| $Sched^2$ | 2019 | GLOBECOM | [Paper](https://ieeexplore.ieee.org/document/9014110) | ♣ | Q-Network based Scheduler | - | - | - | - |
| $FC^2$ | 2019 | CC | [Paper](https://link.springer.com/article/10.1007/s10586-019-02912-6) |  ♦ | Automatic Resource   Configuration  | ✔* | ✔ | - | - |
| Optimus | 2018 | EuroSys | [Paper](https://i.cs.hku.hk/~cwu/papers/yhpeng-eurosys18.pdf) | ♣  | Performance Modelling | - | ✔ | - | [Code](https://github.com/pengyanghua/optimus) |
| OASiS | 2018 | INFOCOM | [Paper](https://ieeexplore.ieee.org/abstract/document/8486422) | ✿♣ | Primal-dual framework | - | ✔ | - | - |
| Gandiva | 2018 | OSDI | [Paper](https://www.usenix.org/conference/osdi18/presentation/xiao) | ✿♣ | Time-slicing; Migration;   Grow-shrink | - | ✔ | ✔ | - |
| Topology-Aware | 2017 | SC | [Paper](https://dl.acm.org/doi/10.1145/3126908.3126933) | ♣ | Best-effort topology-aware placement | - | - | - | [Code](https://github.com/HiEST/gpu-topo-aware) |
| HyperDrive | 2017 | Middleware | [Paper](https://dl.acm.org/doi/10.1145/3135974.3135994) | ♣▲ | Dynamic Probabilistic Accuracy Prediction | - | - | ✔ | - |
| Dorm | 2017 | SMARTCOMP | [Paper](https://www.computer.org/csdl/proceedings-article/smartcomp/2017/07947053/12OmNAlvHZ3) | ♥ | Linear Programming | - | - | - | - |
