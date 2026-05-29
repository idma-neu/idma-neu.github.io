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
