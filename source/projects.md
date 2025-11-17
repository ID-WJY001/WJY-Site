---
title: Projects
date: 2025-10-22 00:00:00
type: page
---

下面示例展示如何在个人站点中列出项目，每个项目带有描述与“查看仓库”按钮：

<!-- 使用简单的卡片布局，兼容 Butterfly 主题的样式 -->
<style>
.projects-grid{display:flex;flex-wrap:wrap;gap:1rem;margin-top:1rem}
.project-card{flex:1 1 calc(33% - 1rem);min-width:220px;background:var(--card-bg,#ffffff);border-radius:8px;padding:1rem;box-shadow:0 2px 8px rgba(0,0,0,0.06)}
.project-card h3{margin-top:0;font-size:1.1rem}
.project-card p{color:var(--meta-color,#666);margin:0.5rem 0}
.project-btn{display:inline-block;margin-top:0.8rem;padding:0.45rem 0.9rem;border-radius:6px;background:var(--accent-color,#49B1F5);color:#fff;text-decoration:none}
@media (max-width:900px){.project-card{flex:1 1 calc(50% - 1rem)}}
@media (max-width:600px){.project-card{flex:1 1 100%}}
</style>

<div class="projects-grid">

<div class="project-card">
  <h3>示例项目 One</h3>
  <p>一个演示项目，展示如何在站点中放置开源仓库链接。</p>
  <a class="project-btn" href="https://github.com/wjydev/example-one" target="_blank" rel="noopener">查看仓库</a>
</div>

<div class="project-card">
  <h3>示例项目 Two</h3>
  <p>另一个示例，包含说明和 GitHub 跳转按钮。</p>
  <a class="project-btn" href="https://github.com/wjydev/example-two" target="_blank" rel="noopener">查看仓库</a>
</div>

<div class="project-card">
  <h3>示例项目 Three</h3>
  <p>可替换为你的真实项目，图片、标签等可自由扩展。</p>
  <a class="project-btn" href="https://github.com/wjydev/example-three" target="_blank" rel="noopener">查看仓库</a>
</div>

</div>

---

说明：

1. 将实际的仓库链接替换为你的 GitHub 仓库 URL。
2. 如果想更可维护，后续可把项目列表放入 `_data/projects.yml` 并修改主题的 include 来自动渲染。