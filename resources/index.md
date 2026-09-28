---
title: 数据资源
nav:
  order: 6
  tooltip: 数据资源
redirect_from:
  - /contact/
---

# {% include icon.html icon="fa-solid fa-database" %}数据资源

{% include section.html %}

## AI for Science

### 生命科学建模

<div class="citation-container">
  <div class="citation">
    <div class="citation-text">
      {% include icon.html icon="fa-solid fa-file-lines" %}
      <a class="citation-title" href="https://arxiv.org/abs/2603.08108">Tau-BNO: Brain Neural Operator for Tau Transport Model</a>
      <div class="citation-description">
        Tau-BNO 面向阿尔茨海默病等 tauopathy 中病理性 tau 蛋白传播建模，使用 Brain Neural Operator 为 Network Transport Model 构建高精度代理仿真器。该方法将初始 tau 分布、动力学参数和脑结构连接组先验解耦建模，在保持方向性传播机制的同时，将复杂 PDE 仿真从小时级加速到秒级，并支持大规模参数探索和机制假设生成。
      </div>
      <div class="citation-details">
        <a href="https://arxiv.org/abs/2603.08108" aria-label="arXiv: 2603.08108" title="arXiv: 2603.08108"><span class="icon resource-link-emoji" aria-hidden="true">📄</span> arXiv:2603.08108</a>
        &nbsp;·&nbsp;
        <a href="https://craft.hengrao.top/BNO-ui/#/" aria-label="BNO Visualization System" title="BNO Visualization System"><span class="icon resource-link-emoji" aria-hidden="true">🧠</span> BNO Visualization</a>
      </div>
    </div>
  </div>
</div>

<div class="citation-container">
  <div class="citation">
    <div class="citation-text">
      {% include icon.html icon="fa-solid fa-code" %}
      <span class="citation-title">A Regime-Aware Trajectory Prediction Framework for 1000+ Systems Biology Models</span>
      <div class="citation-description">
        该工作构建了覆盖 1,050 个 ODE-based systems biology models 的 SysBio-Traj benchmark，涵盖不同生物体、通路和动力学模式，用于评估生物系统长程轨迹预测。RegimeFlow 将稳定、单调、振荡等生物 regime 作为结构化先验注入 conditional flow matching，在未见系统上实现跨系统泛化、不确定性量化和高效长程推理。
      </div>
      <div class="citation-details">
        <a href="https://github.com/hengrao02/RegimeFlow/tree/main" aria-label="GitHub: RegimeFlow" title="GitHub: RegimeFlow">{% include icon.html icon="fa-brands fa-github" %} RegimeFlow</a>
        &nbsp;·&nbsp;
        <a href="https://huggingface.co/datasets/HengRao/SysBio-Traj" aria-label="Hugging Face: SysBio-Traj" title="Hugging Face: SysBio-Traj"><span class="icon" aria-hidden="true">🤗</span> SysBio-Traj</a>
      </div>
    </div>
  </div>
</div>

{% include section.html %}

## 多模态知识图谱补全

<div class="citation-container">
  <div class="citation">
    <div class="citation-text">
      {% include icon.html icon="fa-solid fa-file-lines" %}
      <span class="citation-title">Multimodal Knowledge Graph Completion via Relation-Aware Negative Sampling with Diffusion-Based Interpolation</span>
      <div class="citation-description">
        该工作面向真实世界多模态知识图谱中数据不完整、关系异构以及语义噪声导致的推理可靠性不足问题，提出多模态知识图谱补全框架 RelDINS。该方法首次将关系基数语义建模与扩散式生成负采样相结合，通过关系感知多模态嵌入学习捕获复杂实体关联模式，并利用扩散插值机制生成逐步逼近决策边界的高质量困难负样本，有效提升模型的判别能力和知识推理鲁棒性。RelDINS 在多个公开基准数据集上取得领先性能，为大规模知识图谱自动完善与可信推理提供了高效解决方案。
      </div>
      <div class="citation-details">
        <span>📄 VLDB 2026</span>
        &nbsp;·&nbsp;
        <a href="https://github.com/dailinfei/RelDINS" aria-label="GitHub: RelDINS" title="GitHub: RelDINS">{% include icon.html icon="fa-brands fa-github" %} RelDINS</a>
      </div>
    </div>
  </div>
</div>

<div class="citation-container">
  <div class="citation">
    <div class="citation-text">
      {% include icon.html icon="fa-solid fa-file-lines" %}
      <a class="citation-title" href="https://papers.nips.cc/paper_files/paper/2025/hash/a254abbfdd029d388fc35fd850bbc551-Abstract-Conference.html">LBMKGC: Large Model-Driven Balanced Multimodal Knowledge Graph Completion</a>
      <div class="citation-description">
        该工作面向多模态知识图谱规模化构建与智能推理中的信息缺失、语义异构和知识融合难题，提出大模型驱动的多模态知识图谱补全框架 LBMKGC。该框架借助大规模预训练模型的生成与语义理解能力，实现缺失模态信息的智能恢复，并结合跨模态语义对齐和关系上下文感知融合机制，构建统一、高质量的多源知识表示空间。该研究为下一代知识增强人工智能提供了高效的知识获取与推理基础，可广泛应用于智能搜索、领域知识库构建、推荐决策及大模型知识增强等场景。
      </div>
      <div class="citation-details">
        <a href="https://papers.nips.cc/paper_files/paper/2025/hash/a254abbfdd029d388fc35fd850bbc551-Abstract-Conference.html" aria-label="NeurIPS 2025" title="NeurIPS 2025"><span class="icon resource-link-emoji" aria-hidden="true">📄</span> NeurIPS 2025</a>
        &nbsp;·&nbsp;
        <a href="https://github.com/guoynow/LBMKGC" aria-label="GitHub: LBMKGC" title="GitHub: LBMKGC">{% include icon.html icon="fa-brands fa-github" %} LBMKGC</a>
      </div>
    </div>
  </div>
</div>

{% include section.html %}

## 大模型高效推理

<div class="citation-container">
  <div class="citation">
    <div class="citation-text">
      {% include icon.html icon="fa-solid fa-file-lines" %}
      <a class="citation-title" href="https://aclanthology.org/2026.acl-long.819/">Towards Efficient and Effective Diffusion Language Model Inference via Semantic-Aware Adaptive Denoising</a>
      <div class="citation-description">
        该工作针对扩散语言模型迭代去噪过程中大量冗余计算导致的推理效率问题，提出语义感知自适应去噪框架 Ada-DLM。该方法通过建模 token 置信度的多步演化轨迹，动态识别语义已收敛的 token 并提前停止其计算，同时结合硬件友好的稀疏执行机制，在保持生成质量的同时显著提升推理效率，为高效扩散语言模型推理与部署提供了新的技术路径。
      </div>
      <div class="citation-details">
        <a href="https://aclanthology.org/2026.acl-long.819/" aria-label="ACL 2026" title="ACL 2026"><span class="icon resource-link-emoji" aria-hidden="true">📄</span> ACL 2026</a>
        &nbsp;·&nbsp;
        <a href="https://github.com/fan58085-art/Ada-DLM" aria-label="GitHub: Ada-DLM" title="GitHub: Ada-DLM">{% include icon.html icon="fa-brands fa-github" %} Ada-DLM</a>
      </div>
    </div>
  </div>
</div>

<div class="citation-container">
  <div class="citation">
    <div class="citation-text">
      {% include icon.html icon="fa-solid fa-file-lines" %}
      <a class="citation-title" href="https://openreview.net/forum?id=kY6lHqSE6a">Attention Switch is All You Need: Collaborative Token and KV Compression for Long Video Inference in Hybrid MLLMs</a>
      <div class="citation-description">
        该工作面向 Mamba-Transformer 混合多模态大模型在长视频推理中的高计算与显存开销问题，提出基于 Attention Switch 的协同压缩框架 DeltaInfer。该方法利用 Mamba 原生的 Δ 参数作为轻量级重要性信号，通过帧级语义压缩与 token 级 KV 计算跳过，协同减少 Transformer 的计算量与 KV Cache 开销，在几乎不损失精度的情况下实现最高效的长视频推理。
      </div>
      <div class="citation-details">
        <a href="https://openreview.net/forum?id=kY6lHqSE6a" aria-label="ACM MM 2026" title="ACM MM 2026"><span class="icon resource-link-emoji" aria-hidden="true">📄</span> ACM MM 2026</a>
        &nbsp;·&nbsp;
        <a href="https://github.com/fan58085-art/DeltaInfer" aria-label="GitHub: DeltaInfer" title="GitHub: DeltaInfer">{% include icon.html icon="fa-brands fa-github" %} DeltaInfer</a>
      </div>
    </div>
  </div>
</div>
