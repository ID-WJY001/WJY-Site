---
title: 项目展示
date: 2025-10-22 00:00:00
type: page
---

这里展示我的个人项目，包括开源项目、学习项目等：

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
  <h3>个人博客网站</h3>
  <p>基于 Hexo + Butterfly 主题搭建的个人博客，记录技术与生活。</p>
  <a class="project-btn" href="https://github.com/ID-WJY001/WJY-Site" target="_blank" rel="noopener">查看仓库</a>
</div>

<div class="project-card">
  <h3>项目 2</h3>
  <p>一个基于Python和前端三件套的个性化LLM驱动养成系对话角色引擎。</p>
  <a class="project-btn" href="https://github.com/ID-WJY001/Lyuyuan_AI" target="_blank" rel="noopener">查看仓库</a>
</div>

<div class="project-card">
  <h3>项目 3</h3>
  <p>一个C++编写的Mini_Lisp解释器。</p>
  <a class="project-btn" href="https://github.com/ID-WJY001/Mini_Lisp" target="_blank" rel="noopener">查看仓库</a>
</div>

</div>

---

说明：

1. 将实际的仓库链接替换为你的 GitHub 仓库 URL。
2. 如果想更可维护，后续可把项目列表放入 `_data/projects.yml` 并修改主题的 include 来自动渲染。