# Awesome DL Scheduling Papers

## Schedulers for DL training

| Scheduler | Year | Objective |                   Algorithms                  |          Advantages         |                  Limitations                 | Heterogenous | Elastic | AutoML | Experimental Scale |                  Source Code                 |
|:---------:|:----:|:---------:|:---------------------------------------------:|:---------------------------:|:--------------------------------------------:|:------------:|:-------:|:------:|:------------------:|:--------------------------------------------:|
|  Gandiva  | 2018 |     ✿♣    |     Time-slicing; Migration;   Grow-shrink    |    Better GPU Utilization   |              Framework intrusive             |       -      |    ✔    |    ✔   |          L         |                       -                      |
|  Tiresias | 2019 |     ♣     |  Gittins index;  Least-Attained Service (LAS) |     Information-agnostic    |                       ?                      |       -      |    -    |    -   |          M         |   [Link](https://github.com/SymbioticLab/Tiresias)   |
|   Gavel   | 2020 |     ♣♥    |  Linear Programming; Round-based   Scheduling |     Heterogeneity-Aware     |     Time-consuming and scale   limitation    |       ✔      |    -    |    -   |          M         | [Link](https://github.com/stanford-futuredata/gavel) |
|   Pollux  | 2021 |     ✿♣    | Goodput; Dynamic batch size and learning rate |    Better GPU Utilization   |             Influence to accurcy             |       -      |    ✔    |    ✔   |          L         |       [Link](https://github.com/petuum/adaptdl)      |
|  Synergy  | 2022 |     ♣     |   Optimistic Profiling; Greedy   Scheduling   | Non-dominant resource aware | Less benefit if CPU/Mem are not   bottleneck |       -      |    -    |    -   |          M         |                       -                      |
|   AlloX   | 2020 |           |                                               |                             |                                              |      ✔*      |         |        |                    |                                              |