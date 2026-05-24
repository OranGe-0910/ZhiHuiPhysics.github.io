---
permalink: /
title: "智绘物理"
author_profile: false
classes: wide
hide_title: true
redirect_from:
  - /about/
  - /about.html
---

<section class="zh-home-hero">
  <div class="zh-home-hero__content">
    <p class="zh-kicker">大学生创新创业项目展示</p>
    <h1>智绘物理</h1>
    <h2>大学物理交互式动画模型库</h2>
    <p>
      用可视化与交互实验呈现抽象物理规律，融合 AI 辅助设计、Manim 公式推导、前端交互模型与 GitHub Pages 部署，
      建设面向课堂演示、课后探索和项目汇报的轻量化学习平台。
    </p>
    <div class="zh-actions">
      <a class="zh-button" href="/publications/">进入模型库</a>
      <a class="zh-button zh-button--ghost" href="#technical-route">查看技术路线</a>
    </div>
  </div>
  <div class="zh-home-hero__visual" aria-hidden="true">
    <svg viewBox="0 0 520 360" role="img">
      <defs>
        <linearGradient id="heroLine" x1="0" x2="1" y1="0" y2="1">
          <stop offset="0" stop-color="#19B5FE"/>
          <stop offset="1" stop-color="#2F80ED"/>
        </linearGradient>
      </defs>
      <rect x="36" y="42" width="448" height="276" rx="20" fill="#FFFFFF"/>
      <path d="M72 260 C135 142 208 300 270 170 S395 72 454 134" fill="none" stroke="url(#heroLine)" stroke-width="8" stroke-linecap="round"/>
      <path d="M96 98 h130 m-88 34 h188 m-156 34 h250" stroke="#D8E7FA" stroke-width="8" stroke-linecap="round"/>
      <circle cx="146" cy="206" r="18" fill="#19B5FE"/>
      <circle cx="292" cy="168" r="24" fill="#2F80ED"/>
      <circle cx="424" cy="116" r="14" fill="#123B7A"/>
      <path d="M122 272 h300" stroke="#123B7A" stroke-width="5" stroke-linecap="round"/>
      <path d="M360 254 l36 18 -36 18" fill="none" stroke="#123B7A" stroke-width="5" stroke-linecap="round" stroke-linejoin="round"/>
    </svg>
  </div>
</section>

<section class="zh-section">
  <div class="zh-section-head">
    <p class="zh-kicker">Module Library</p>
    <h2>四大物理模块</h2>
    <p>围绕大学物理核心知识点组织模型资源，便于现场汇报中快速进入对应演示场景。</p>
  </div>
  <div class="zh-module-grid">
    <article class="zh-module-card zh-module-card--mechanics">
      <div class="zh-card-icon" aria-hidden="true">
        <svg viewBox="0 0 80 80">
          <path d="M12 60 C26 28 48 26 68 42" fill="none" stroke="currentColor" stroke-width="6" stroke-linecap="round"/>
          <circle cx="28" cy="42" r="9" fill="currentColor"/>
          <path d="M44 42 h20 l-8 -8 m8 8 l-8 8" fill="none" stroke="currentColor" stroke-width="5" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
      <span class="zh-tag">已上线 1 个模型</span>
      <h3>力学</h3>
      <p>展示速度分解、运动约束、碰撞与能量转化等经典运动规律。</p>
      <a class="zh-card-link" href="/publications/">进入模块</a>
    </article>
    <article class="zh-module-card zh-module-card--thermal">
      <div class="zh-card-icon" aria-hidden="true">
        <svg viewBox="0 0 80 80">
          <path d="M26 56 V24 a14 14 0 0 1 28 0 v32" fill="none" stroke="currentColor" stroke-width="6" stroke-linecap="round"/>
          <circle cx="40" cy="58" r="14" fill="currentColor"/>
          <path d="M18 22 c6 -8 12 8 18 0 s12 -8 18 0 12 8 18 0" fill="none" stroke="currentColor" stroke-width="4" stroke-linecap="round"/>
        </svg>
      </div>
      <span class="zh-tag">规划建设中</span>
      <h3>热学</h3>
      <p>围绕热流、温度分布、分子运动和热力学过程建设可视化实验。</p>
      <a class="zh-card-link" href="/talks/">进入模块</a>
    </article>
    <article class="zh-module-card zh-module-card--em">
      <div class="zh-card-icon" aria-hidden="true">
        <svg viewBox="0 0 80 80">
          <path d="M14 40 C26 18 54 18 66 40 C54 62 26 62 14 40Z" fill="none" stroke="currentColor" stroke-width="5"/>
          <path d="M24 40 h32 m-8 -8 l8 8 -8 8" fill="none" stroke="currentColor" stroke-width="5" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M18 18 C44 30 36 50 62 62" fill="none" stroke="currentColor" stroke-width="4" stroke-linecap="round"/>
        </svg>
      </div>
      <span class="zh-tag">已上线 2 个模型</span>
      <h3>电磁学</h3>
      <p>通过电场线、电通量和高斯面演示空间场与源之间的关系。</p>
      <a class="zh-card-link" href="/teaching/">进入模块</a>
    </article>
    <article class="zh-module-card zh-module-card--optics">
      <div class="zh-card-icon" aria-hidden="true">
        <svg viewBox="0 0 80 80">
          <path d="M38 12 C26 28 26 52 38 68 M42 12 C54 28 54 52 42 68" fill="none" stroke="currentColor" stroke-width="5" stroke-linecap="round"/>
          <path d="M10 26 h24 M10 54 h24 M46 26 h24 M46 54 h24" stroke="currentColor" stroke-width="4" stroke-linecap="round"/>
          <path d="M34 26 l12 12 m0 4 L34 54" fill="none" stroke="currentColor" stroke-width="4" stroke-linecap="round"/>
        </svg>
      </div>
      <span class="zh-tag">已上线 1 个模型</span>
      <h3>光学</h3>
      <p>用光线追迹和透镜参数调节展示成像位置、大小与正倒关系。</p>
      <a class="zh-card-link" href="/portfolio/">进入模块</a>
    </article>
  </div>
</section>

<section class="zh-section" id="online-models">
  <div class="zh-section-head">
    <p class="zh-kicker">Model Showcase</p>
    <h2>已上线模型展示</h2>
    <p>优先展示已可访问的交互模型；未提供独立路径的模型以建设条目形式保留在模型库规划中。</p>
  </div>
  <div class="zh-showcase-grid">
    <article class="zh-showcase-card zh-showcase-card--planned">
      <span class="zh-pill">建设条目</span>
      <h3>动量守恒与碰撞</h3>
      <p>面向碰撞前后速度、动量与能量变化的实验模型，作为力学模块后续重点扩展方向。</p>
    </article>
    <article class="zh-showcase-card">
      <span class="zh-pill">力学</span>
      <h3>绳拉船问题</h3>
      <p>观察绳速、夹角与船速之间的投影关系。</p>
      <a href="https://orange-0910.github.io/ZhiHuiPhysics.github.io/assets/interactive/mechanics/boat-velocity/dist/index.html" target="_blank" rel="noopener">全屏打开</a>
    </article>
    <article class="zh-showcase-card">
      <span class="zh-pill">电磁学</span>
      <h3>均匀带电圆环电场</h3>
      <p>观察圆环轴线上电场强度随距离变化的规律。</p>
      <a href="https://orange-0910.github.io/ZhiHuiPhysics.github.io/assets/interactive/electromagnetism/electric-ring-field/dist/index.html" target="_blank" rel="noopener">全屏打开</a>
    </article>
    <article class="zh-showcase-card">
      <span class="zh-pill">电磁学</span>
      <h3>高斯定理与电通量</h3>
      <p>比较高斯面内外电荷对总电通量的影响。</p>
      <a href="https://orange-0910.github.io/ZhiHuiPhysics.github.io/assets/interactive/electromagnetism/gauss-theorem-demo/dist/index.html" target="_blank" rel="noopener">全屏打开</a>
    </article>
  </div>
</section>

<section class="zh-section" id="technical-route">
  <div class="zh-section-head">
    <p class="zh-kicker">Technical Route</p>
    <h2>技术路线</h2>
  </div>
  <div class="zh-timeline">
    <div>
      <span>01</span>
      <strong>AI 辅助策划</strong>
      <p>整理知识点、交互目标与模型原型。</p>
    </div>
    <div>
      <span>02</span>
      <strong>Manim 公式推导</strong>
      <p>将物理公式和推导过程转化为动态表达。</p>
    </div>
    <div>
      <span>03</span>
      <strong>前端交互模型</strong>
      <p>实现参数调节、实时反馈和页面内实验。</p>
    </div>
    <div>
      <span>04</span>
      <strong>GitHub Pages 展示</strong>
      <p>以静态站点持续发布和迭代模型库。</p>
    </div>
  </div>
</section>
