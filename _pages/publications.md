---
layout: single
title: "力学模块"
permalink: /publications/
collection: publications
author_profile: false
classes: wide
hide_title: true
---

<section class="zh-module-hero zh-module-hero--mechanics">
  <div>
    <p class="zh-kicker">Mechanics Module</p>
    <h1>力学模块</h1>
    <p>
      面向运动学、速度分解、几何约束与动量守恒等核心概念，构建可观察、可调节、可投屏展示的交互实验。
    </p>
    <div class="zh-tag-row">
      <span>运动学</span>
      <span>速度分解</span>
      <span>几何约束</span>
      <span>碰撞与动量</span>
    </div>
  </div>
  <div class="zh-hero-illustration" aria-hidden="true">
    <svg viewBox="0 0 260 190">
      <path d="M24 148 C76 48 150 48 236 112" fill="none" stroke="currentColor" stroke-width="8" stroke-linecap="round"/>
      <circle cx="82" cy="104" r="17" fill="currentColor"/>
      <circle cx="160" cy="86" r="13" fill="#19B5FE"/>
      <path d="M114 102 h72 l-18 -16 m18 16 l-18 16" fill="none" stroke="#123B7A" stroke-width="7" stroke-linecap="round" stroke-linejoin="round"/>
      <path d="M32 158 h194" stroke="#D8E7FA" stroke-width="6" stroke-linecap="round"/>
    </svg>
  </div>
</section>

<section class="zh-section">
  <div class="zh-section-head">
    <p class="zh-kicker">Interactive Lab</p>
    <h2>交互模型实验区</h2>
    <p>
      本模块优先展示与运动学、几何约束和速度关系相关的交互模型，适合课堂讲解、课后探索和项目汇报展示。
    </p>
  </div>

  <details class="zh-model-card" open>
    <summary>
      <span>重点模型</span>
      <strong>绳拉船问题：速度分解交互模型</strong>
    </summary>
    <div class="zh-model-body">
      <p>
        模型展示绳以恒定速度收紧时，船的水平速度如何由绳长、夹角和速度投影关系共同决定。
      </p>
      <div class="zh-tag-row zh-tag-row--small">
        <span>速度投影</span>
        <span>矢量分解</span>
        <span>几何约束</span>
      </div>
      <div class="zh-model-meta">
        <strong>建议观察点</strong>
        <ul>
          <li>绳与水平方向夹角变化时，船速如何变化。</li>
          <li>船速与绳速之间是否满足速度投影关系。</li>
          <li>几何约束如何影响实际运动速度。</li>
        </ul>
      </div>
      <div class="zh-actions">
        <a class="zh-button zh-button--ghost" href="#frame-boat">页面内体验</a>
        <a class="zh-button" href="https://orange-0910.github.io/ZhiHuiPhysics.github.io/assets/interactive/mechanics/boat-velocity/dist/index.html" target="_blank" rel="noopener">全屏打开模型</a>
      </div>
      <div class="zh-frame-shell" id="frame-boat" style="--model-height: 900px;">
        <div class="zh-frame-bar">
          <span>实验窗口</span>
          <strong>绳拉船速度分解</strong>
        </div>
        <div class="zh-frame-scroll">
          <iframe
            src="https://orange-0910.github.io/ZhiHuiPhysics.github.io/assets/interactive/mechanics/boat-velocity/dist/index.html"
            title="绳拉船速度分解模型"
            loading="lazy"
            allowfullscreen>
          </iframe>
        </div>
      </div>
    </div>
  </details>

  <details class="zh-model-card">
    <summary>
      <span>交互模型</span>
      <strong>圆弧槽物理系统</strong>
    </summary>
    <div class="zh-model-body">
      <p>
        模型展示小球在圆弧槽中的运动过程。通过调节圆弧槽质量、小球质量、边长和动画速度等参数，
        可以观察小球滑动到底端时的位移、速度、角度和运动时间变化。
      </p>
      <div class="zh-tag-row zh-tag-row--small">
        <span>曲线运动</span>
        <span>几何约束</span>
        <span>运动学分析</span>
      </div>
      <div class="zh-model-meta">
        <strong>建议观察点</strong>
        <ul>
          <li>小球在圆弧槽中运动时，理论位移与实际位移如何变化。</li>
          <li>改变小球质量和圆弧槽质量后，系统运动结果是否发生明显变化。</li>
          <li>改变边长参数后，小球滑到底端所需时间和运动轨迹如何变化。</li>
          <li>模型中的速度、角度、位移和时间之间有什么对应关系。</li>
        </ul>
      </div>
      <div class="zh-actions">
        <a class="zh-button zh-button--ghost" href="#frame-arc-slot">页面内体验</a>
        <a class="zh-button" href="https://orange-0910.github.io/ZhiHuiPhysics.github.io/assets/interactive/optics/lens-sim/dist/index.html" target="_blank" rel="noopener">全屏打开模型</a>
      </div>
      <div class="zh-frame-shell" id="frame-arc-slot" style="--model-height: 950px;">
        <div class="zh-frame-bar">
          <span>实验窗口</span>
          <strong>圆弧槽物理系统</strong>
        </div>
        <div class="zh-frame-scroll">
          <iframe
            src="https://orange-0910.github.io/ZhiHuiPhysics.github.io/assets/interactive/optics/lens-sim/dist/index.html"
            title="圆弧槽物理系统"
            loading="lazy"
            allowfullscreen>
          </iframe>
        </div>
      </div>
    </div>
  </details>

  <article class="zh-planned-card">
    <span class="zh-pill">后续模型</span>
    <h3>动量守恒与碰撞</h3>
    <p>
      该模型将用于展示碰撞前后速度、动量与能量变化。当前仓库尚未提供独立交互模型路径，
      因此本页暂不嵌入占位 iframe，避免产生失效链接。
    </p>
  </article>
</section>

<section class="zh-section">
  <div class="zh-use-grid">
    <div>
      <strong>课堂演示</strong>
      <p>用于讲解速度分解、约束关系、曲线运动和物理量变化过程。</p>
    </div>
    <div>
      <strong>课后探索</strong>
      <p>支持学习者调节参数，自主验证公式、图像和运动过程之间的关系。</p>
    </div>
    <div>
      <strong>项目汇报</strong>
      <p>可在投屏场景中快速展示交互模型的开发成果和网页端运行效果。</p>
    </div>
  </div>
</section>
