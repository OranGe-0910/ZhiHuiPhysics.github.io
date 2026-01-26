---
title: "力学模块：经典运动与能量守恒"
collection: publications
category: modules
permalink: /publications/mechanics-module
excerpt: "本模块聚焦于经典力学的核心知识，涵盖牛顿运动定律、动量守恒与能量转化等关键概念。"
venue: "智绘物理 · 力学单元"
paperurl: "https://orange-0910.github.io/ZhiHuiPhysics.github.io/"
citation: "智绘物理团队 (2025). 『力学模块：经典运动与能量守恒』. 智绘物理项目，大学物理创新教学系列."
classes: wide
---

力学模块是“智绘物理”项目的核心部分之一，主要展示物体运动与相互作用的动态规律。  
通过生成式AI与物理仿真技术，本模块以动画形式可视化经典力学中的重要现象，  
帮助学习者直观理解力、加速度与能量之间的关系。

重点内容包括：
---

## 力学交互实验区

下面收录本模块已上线的交互模型。建议先看“实验目的”，再进入交互操作。

<ul>
  <li><a href="#exp-momentum">动量守恒与碰撞</a></li>
  <li><a href="#exp-boat">绳拉船问题（速度分解）</a></li>
  <!-- 未来：<li><a href="#exp-arc">圆弧槽系统</a></li> -->
</ul>

<hr/>

<details id="exp-momentum" open>
  <summary><strong>动量守恒与碰撞（交互模型）</strong>（点击展开/收起）</summary>
  <p>用于展示碰撞过程中系统动量的变化与守恒规律。可调整质量、初速度等参数，观察不同碰撞情形。</p>

  <p>
    👉 <a href="https://orange-0910.github.io/ZhiHuiPhysics.github.io/assets/interactive/optics/lens-sim/dist/index.html" target="_blank">
      单独打开（更大更流畅）
    </a>
  </p>

  <iframe
    src="https://orange-0910.github.io/ZhiHuiPhysics.github.io/assets/interactive/optics/lens-sim/dist/index.html"
    width="100%"
    height="1000"
    style="border:0; border-radius:12px;"
    loading="lazy"
    allowfullscreen>
  </iframe>

  <p><strong>观察点：</strong>总动量是否守恒？弹性/非弹性碰撞的差异是什么？</p>
</details>

<br/>

<details id="exp-boat">
  <summary><strong>绳拉船问题（速度分解交互模型）</strong>（点击展开/收起）</summary>
  <p>展示“绳以恒定速度收紧”时，船的水平速度如何由几何关系决定。可观察速度分解示意图与船速变化。</p>

  <p>
    👉 <a href="https://orange-0910.github.io/ZhiHuiPhysics.github.io/assets/interactive/mechanics/boat-velocity/dist/index.html" target="_blank">
      单独打开（更大更流畅）
    </a>
  </p>

  <iframe
    src="https://orange-0910.github.io/ZhiHuiPhysics.github.io/assets/interactive/mechanics/boat-velocity/dist/index.html"
    width="100%"
    height="1050"
    style="border:0; border-radius:12px;"
    loading="lazy"
    allowfullscreen>
  </iframe>

  <p><strong>观察点：</strong>当夹角变化时，船速如何变化？与 <code>v船 = v绳 / cosθ</code> 的关系是否一致？</p>
</details>
