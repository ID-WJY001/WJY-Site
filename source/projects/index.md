---
title: Projects
date: 2025-11-18 14:53:39
type: page
---

Here are my personal projects, including open-source and learning projects:

<style>
.projects-container{max-width:1200px;margin:2rem auto;padding:0 1rem}
.projects-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(320px,1fr));gap:2rem;margin-top:2rem}
.project-card{position:relative;background:linear-gradient(135deg,#667eea 0%,#764ba2 100%);border-radius:16px;padding:1.5rem;box-shadow:0 8px 24px rgba(102,126,234,0.15);transition:all 0.4s cubic-bezier(0.175,0.885,0.32,1.275);overflow:hidden}
.project-card::before{content:'';position:absolute;top:0;left:0;right:0;bottom:0;background:rgba(255,255,255,0.05);opacity:0;transition:opacity 0.3s}
.project-card:hover{transform:translateY(-8px) scale(1.02);box-shadow:0 16px 48px rgba(102,126,234,0.3)}
.project-card:hover::before{opacity:1}
.project-card:nth-child(2){background:linear-gradient(135deg,#f093fb 0%,#f5576c 100%)}
.project-card:nth-child(3){background:linear-gradient(135deg,#4facfe 0%,#00f2fe 100%)}
.project-header{display:flex;align-items:center;margin-bottom:1rem}
.project-icon{font-size:2.5rem;margin-right:0.8rem}
.project-card h3{margin:0;font-size:1.4rem;color:#fff;font-weight:600;text-shadow:0 2px 4px rgba(0,0,0,0.1)}
.project-card p{color:rgba(255,255,255,0.95);margin:1rem 0;font-size:0.95rem;line-height:1.6}
.project-meta{display:flex;gap:0.8rem;margin:1rem 0;flex-wrap:wrap}
.project-tag{display:inline-block;padding:0.3rem 0.8rem;background:rgba(255,255,255,0.2);border-radius:20px;font-size:0.85rem;color:#fff;backdrop-filter:blur(10px)}
.project-btn{display:inline-flex;align-items:center;gap:0.5rem;margin-top:1rem;padding:0.7rem 1.5rem;border-radius:30px;background:rgba(255,255,255,0.95);color:#667eea;font-weight:600;text-decoration:none;transition:all 0.3s;box-shadow:0 4px 12px rgba(0,0,0,0.1)}
.project-btn:hover{background:#fff;transform:translateX(4px);box-shadow:0 6px 20px rgba(0,0,0,0.15)}
@media (max-width:768px){.projects-grid{grid-template-columns:1fr;gap:1.5rem}}
</style>

<div class="projects-container">
<div class="projects-grid">

<div class="project-card">
  <div class="project-header">
    <span class="project-icon">🌐</span>
    <h3>Personal Blog</h3>
  </div>
  <p>A personal blog built with Hexo + Fluid theme, documenting tech insights and life experiences.</p>
  <div class="project-meta">
    <span class="project-tag">Hexo</span>
    <span class="project-tag">JavaScript</span>
    <span class="project-tag">Blog</span>
  </div>
  <a class="project-btn" href="https://github.com/ID-WJY001/WJY-Site" target="_blank" rel="noopener">
    <span>View on GitHub</span>
    <span>→</span>
  </a>
</div>

<div class="project-card">
  <div class="project-header">
    <span class="project-icon">🤖</span>
    <h3>Lyuyuan AI</h3>
  </div>
  <p>An LLM-powered conversational character engine with personalized AI companions, built with Python and modern web technologies.</p>
  <div class="project-meta">
    <span class="project-tag">Python</span>
    <span class="project-tag">LLM</span>
    <span class="project-tag">AI</span>
  </div>
  <a class="project-btn" href="https://github.com/ID-WJY001/Lyuyuan_AI" target="_blank" rel="noopener">
    <span>View on GitHub</span>
    <span>→</span>
  </a>
</div>

<div class="project-card">
  <div class="project-header">
    <span class="project-icon">⚡</span>
    <h3>Mini Lisp Interpreter</h3>
  </div>
  <p>A lightweight Lisp interpreter implemented in C++, featuring core functional programming capabilities.</p>
  <div class="project-meta">
    <span class="project-tag">C++</span>
    <span class="project-tag">Compiler</span>
    <span class="project-tag">Lisp</span>
  </div>
  <a class="project-btn" href="https://github.com/ID-WJY001/Mini_Lisp" target="_blank" rel="noopener">
    <span>View on GitHub</span>
    <span>→</span>
  </a>
</div>

</div>
</div>
