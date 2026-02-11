---
layout: default
title: 个人作品集
cover_title: 狂小克 · 个人作品集
cover_subtitle: 参考 Notion 信息架构重做的 portfolio，收录产品、游戏项目与研究论文。
---

<div class="page-card callout">
  <p>你提到页面太素，这版开始加入了项目素材图：游戏图来自 <code>re0答辩最终版.pptx</code>，论文图来自 <code>826_file_paper.pdf</code> 首页面截图。</p>
</div>

<section class="page-card">
  <h2>视觉预览</h2>
  <div class="preview-grid">
    <a class="preview-card" href="{{ '/projects/re0-hust-life' | relative_url }}">
      <img src="{{ '/assets/images/re0/cover.png' | relative_url }}" alt="Re0 封面图" loading="lazy" />
      <p>Re0 项目封面</p>
    </a>
    <a class="preview-card" href="{{ '/projects/re0-hust-life' | relative_url }}">
      <img src="{{ '/assets/images/re0/event-boar.png' | relative_url }}" alt="Re0 事件截图" loading="lazy" />
      <p>Re0 事件分支截图</p>
    </a>
    <a class="preview-card" href="{{ '/projects/research-paper' | relative_url }}">
      <img src="{{ '/assets/images/paper/workflow-key-figure.png' | relative_url }}" alt="论文关键图截图" loading="lazy" />
      <p>读研论文关键图截图</p>
    </a>
  </div>
</section>

<section class="page-card">
  <h2>Projects Database</h2>
  <div class="db-table">
    <div class="db-head">
      <div>作品</div>
      <div>类型</div>
      <div>一句话简介</div>
      <div>详情</div>
    </div>

    <div class="db-row">
      <div><a class="project-link" href="{{ '/projects/re0-hust-life' | relative_url }}">Re0：从 0 开始的 HUST 生活</a></div>
      <div><span class="tag">游戏项目</span></div>
      <div class="meta">大学四年选择模拟叙事，基于属性与事件驱动多结局。</div>
      <div><a class="btn" href="{{ '/projects/re0-hust-life' | relative_url }}">查看</a></div>
    </div>

    <div class="db-row">
      <div><a class="project-link" href="{{ '/projects/weiban-openapi' | relative_url }}">微伴助手 OpenAPI</a></div>
      <div><span class="tag">产品 / 平台</span></div>
      <div class="meta">夜莺科技阶段核心方向之一，面向开发者的开放接口能力。</div>
      <div><a class="btn" href="{{ '/projects/weiban-openapi' | relative_url }}">查看</a></div>
    </div>

    <div class="db-row">
      <div><a class="project-link" href="{{ '/projects/early-2025-mini-project' | relative_url }}">年初小作品（飞书 Wiki）</a></div>
      <div><span class="tag">小型项目</span></div>
      <div class="meta">年初完成的实践项目，当前收录外链与后续补充提纲。</div>
      <div><a class="btn" href="{{ '/projects/early-2025-mini-project' | relative_url }}">查看</a></div>
    </div>

    <div class="db-row">
      <div><a class="project-link" href="{{ '/projects/research-paper' | relative_url }}">LGD 论文（读研期间）</a></div>
      <div><span class="tag">研究论文</span></div>
      <div class="meta">LLM 驱动的 DSA 代码生成框架研究，论文 PDF 已收录。</div>
      <div><a class="btn" href="{{ '/projects/research-paper' | relative_url }}">查看</a></div>
    </div>
  </div>
</section>

<section class="grid-2">
  <article class="page-card">
    <h3>我在做什么</h3>
    <ul class="list-tight">
      <li>把项目文档从“仅链接”升级为可阅读 case study。</li>
      <li>沉淀产品工作方法：需求拆解、接口定义、接入体验优化。</li>
      <li>持续补充可量化结果（效率、覆盖范围、用户反馈）。</li>
    </ul>
  </article>

  <article class="page-card">
    <h3>快速入口</h3>
    <p>
      <a class="btn btn-primary" href="https://openapi.weibanzhushou.com/" target="_blank" rel="noopener noreferrer">访问 OpenAPI</a>
      <a class="btn" href="{{ '/assets/papers/826_file_paper.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">下载论文 PDF</a>
    </p>
    <p class="meta">若你在招聘 / 合作场景访问，可直接从这里获取最核心材料。</p>
  </article>
</section>
