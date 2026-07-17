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
