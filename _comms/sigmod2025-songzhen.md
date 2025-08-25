---
title: ACM SIGMOD/PODS International Conference on Management of Data（SIGMOD 2025）, Santiago, Chile.
image: images/comm/sigmod2024-songzhen.png
---

宋振本次汇报的论文题目为“SWASH: A Flexible Communication Framework with Sliding-Window-Based Cache Sharing for Scalable DGNN Training”。

该研究针对分布式动态图神经网络训练中多时间快照的高复杂度计算、通信开销大、负载均衡难以控制等挑战，创新性地提出了一种基于滑动窗口缓存共享的灵活通信框架。该框架支持在任意时刻以任意比例高效进行顶点嵌入通信，结合自适应调度策略与轻量级图划分方法，并利用缓存共享机制在滑动窗口内跨快照传递信息，有效减少了通信次数，缓解了信息丢失带来的准确率下降。在多个数据集和实验环境下，SWASH系统相较于现有最先进滑动窗口框架实现了平均9.44倍的加速，同时保持了与全通信、无缓存方案一致的模型准确率。该成果可广泛应用于社交网络分析、交通流预测、知识图谱推理等大规模动态图处理场景，具有重要的理论意义和应用价值

{%
  include figure.html
  image="images/comm/sigmod2025-songzhen-1.png"
%}