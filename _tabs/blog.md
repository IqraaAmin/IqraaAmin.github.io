---
layout: page
icon: fas fa-newspaper
order: 5
title: Articles
permalink: /blog/
---

<style>
  .iq-blog-page * { box-sizing: border-box; }
  .iq-blog-page {
    font-family: 'Inter', sans-serif;
  }

  .iq-blog-page .page-sub {
    color: #7f8fa6;
    font-size: 13px;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-bottom: 28px;
  }

  /* Category cards */
  .iq-cat-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 16px;
    margin-bottom: 44px;
  }
  .iq-cat-card {
    border-radius: 10px;
    overflow: hidden;
    text-decoration: none;
    position: relative;
    aspect-ratio: 16/9;
    display: block;
  }
  .iq-cat-card img {
    width: 100%; height: 100%;
    object-fit: cover;
    transition: transform .4s;
  }
  .iq-cat-card:hover img { transform: scale(1.05); }
  .iq-cat-overlay {
    position: absolute; inset: 0;
    background: linear-gradient(to top, rgba(10,10,12,0.88) 0%, rgba(10,10,12,0.1) 100%);
    display: flex; flex-direction: column; justify-content: flex-end;
    padding: 14px;
  }
  .iq-cat-label {
    font-size: 10px; font-weight: 700; color: #89b4fa;
    text-transform: uppercase; letter-spacing: 1px; margin-bottom: 2px;
  }
  .iq-cat-name { font-size: 15px; font-weight: 700; color: #fff; }
  .iq-cat-count { font-size: 11px; color: rgba(255,255,255,0.65); }

  /* Section title */
  .iq-section-title {
    font-size: 21px; font-weight: 700;
    margin: 0 0 18px;
    padding-bottom: 8px;
    border-bottom: 1px solid rgba(127,140,156,0.25);
  }

  /* Article list */
  .iq-article-list { margin-bottom: 44px; }
  .iq-article-card {
    display: flex; gap: 16px;
    text-decoration: none; color: inherit;
    padding: 14px 0;
    border-bottom: 1px solid rgba(127,140,156,0.12);
  }
  .iq-article-card:last-child { border-bottom: none; }
  .iq-article-thumb {
    width: 130px; height: 90px;
    border-radius: 8px;
    object-fit: cover;
    flex-shrink: 0;
  }
  .iq-article-body { flex: 1; min-width: 0; }
  .iq-article-date {
    font-size: 12px; color: #7f8fa6; margin-bottom: 4px;
  }
  .iq-article-title {
    font-size: 16px; font-weight: 700; margin-bottom: 6px;
  }
  .iq-article-card:hover .iq-article-title { color: #89b4fa; }
  .iq-article-excerpt {
    font-size: 13.5px; color: #7f8fa6;
    margin-bottom: 8px;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
    overflow: hidden;
  }
  .iq-article-tag {
    font-size: 11px; font-weight: 600;
    background: rgba(137,180,250,0.12);
    color: #89b4fa;
    padding: 3px 9px;
    border-radius: 5px;
  }

  @media (max-width: 700px) {
    .iq-cat-grid { grid-template-columns: 1fr 1fr; }
    .iq-article-thumb { width: 90px; height: 70px; }
  }
</style>

<div class="iq-blog-page">
  <p class="page-sub">Posts, updates, and personal writing</p>

  <!-- Category cards -->
  <div class="iq-cat-grid">
    <a class="iq-cat-card" href="#introduction">
      <img src="https://images.pexels.com/photos/33327129/pexels-photo-33327129.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Introduction" />
      <div class="iq-cat-overlay">
        <div class="iq-cat-label">Category</div>
        <div class="iq-cat-name">Introduction</div>
        <div class="iq-cat-count">3 articles</div>
      </div>
    </a>
    <a class="iq-cat-card" href="#programming-fundamentals">
      <img src="https://images.pexels.com/photos/574071/pexels-photo-574071.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Programming Fundamentals" />
      <div class="iq-cat-overlay">
        <div class="iq-cat-label">Category</div>
        <div class="iq-cat-name">Programming Fundamentals</div>
        <div class="iq-cat-count">1 article</div>
      </div>
    </a>
    <a class="iq-cat-card" href="#data-ml">
      <img src="https://images.pexels.com/photos/7947996/pexels-photo-7947996.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Data & Machine Learning" />
      <div class="iq-cat-overlay">
        <div class="iq-cat-label">Category</div>
        <div class="iq-cat-name">Data &amp; Machine Learning</div>
        <div class="iq-cat-count">5 articles</div>
      </div>
    </a>
  </div>

  <!-- Introduction -->
  <h2 class="iq-section-title" id="introduction">Introduction</h2>
  <div class="iq-article-list">

    <a class="iq-article-card" href="/posts/welcome/">
      <img class="iq-article-thumb" src="https://images.pexels.com/photos/33327129/pexels-photo-33327129.jpeg?auto=compress&cs=tinysrgb&w=400" alt="" />
      <div class="iq-article-body">
        <div class="iq-article-date">March 29, 2026</div>
        <div class="iq-article-title">Welcome to My Blog</div>
        <div class="iq-article-excerpt">Why I started writing in public, and what this space is going to be used for as I move through my engineering degree.</div>
        <span class="iq-article-tag">Introduction</span>
      </div>
    </a>

    <a class="iq-article-card" href="/posts/my-first-experience-with-programming/">
      <img class="iq-article-thumb" src="https://images.pexels.com/photos/5483075/pexels-photo-5483075.jpeg?auto=compress&cs=tinysrgb&w=400" alt="" />
      <div class="iq-article-body">
        <div class="iq-article-date">April 02, 2026</div>
        <div class="iq-article-title">My First Experience with Programming</div>
        <div class="iq-article-excerpt">The first lines of code I ever wrote, what confused me, and the moment something finally clicked.</div>
        <span class="iq-article-tag">Introduction</span>
      </div>
    </a>

    <a class="iq-article-card" href="/posts/my-journey-to-uet/">
      <img class="iq-article-thumb" src="https://images.pexels.com/photos/7972502/pexels-photo-7972502.jpeg?auto=compress&cs=tinysrgb&w=400" alt="" />
      <div class="iq-article-body">
        <div class="iq-article-date">April 02, 2026</div>
        <div class="iq-article-title">My Journey to UET Faisalabad</div>
        <div class="iq-article-excerpt">How I landed in Computer Engineering at UET — the decisions, the doubts, and the day it became real.</div>
        <span class="iq-article-tag">Introduction</span>
      </div>
    </a>

  </div>

  <!-- Programming Fundamentals -->
  <h2 class="iq-section-title" id="programming-fundamentals">Programming Fundamentals</h2>
  <div class="iq-article-list">

    <a class="iq-article-card" href="/posts/Challenges-i-faced-in-pf-lab/">
      <img class="iq-article-thumb" src="https://images.pexels.com/photos/6684150/pexels-photo-6684150.jpeg?auto=compress&cs=tinysrgb&w=400" alt="" />
      <div class="iq-article-body">
        <div class="iq-article-date">May 21, 2026</div>
        <div class="iq-article-title">Challenges I Faced in Programming Fundamentals (PF) Lab</div>
        <div class="iq-article-excerpt">The bugs that wouldn't die, the late nights in lab, and what the PF course actually taught me about thinking in code.</div>
        <span class="iq-article-tag">Programming Fundamentals</span>
      </div>
    </a>

  </div>

  <!-- Data & Machine Learning -->
  <h2 class="iq-section-title" id="data-ml">Data &amp; Machine Learning</h2>
  <div class="iq-article-list">

    <a class="iq-article-card" href="/posts/Advanced-pandas/">
      <img class="iq-article-thumb" src="https://images.pexels.com/photos/7988114/pexels-photo-7988114.jpeg?auto=compress&cs=tinysrgb&w=400" alt="" />
      <div class="iq-article-body">
        <div class="iq-article-date">May 18, 2026</div>
        <div class="iq-article-title">Advanced Pandas: GroupBy, Merge and Data Cleaning Techniques</div>
        <div class="iq-article-excerpt">Going beyond basic dataframes — grouping, merging, and cleaning real, messy data with pandas.</div>
        <span class="iq-article-tag">Data &amp; ML</span>
      </div>
    </a>

    <a class="iq-article-card" href="/posts/My-overall-learning-journey/">
      <img class="iq-article-thumb" src="https://images.pexels.com/photos/7947996/pexels-photo-7947996.jpeg?auto=compress&cs=tinysrgb&w=400" alt="" />
      <div class="iq-article-body">
        <div class="iq-article-date">May 19, 2026</div>
        <div class="iq-article-title">My Overall Learning Journey: From Basics to AI and Data Science</div>
        <div class="iq-article-excerpt">Looking back at how far I've come — from "hello world" to my first real steps into AI and data science.</div>
        <span class="iq-article-tag">Data &amp; ML</span>
      </div>
    </a>

    <a class="iq-article-card" href="/posts/The-language-of-database/">
      <img class="iq-article-thumb" src="https://images.pexels.com/photos/574071/pexels-photo-574071.jpeg?auto=compress&cs=tinysrgb&w=400" alt="" />
      <div class="iq-article-body">
        <div class="iq-article-date">May 28, 2026</div>
        <div class="iq-article-title">Learning SQL: The Language of Databases</div>
        <div class="iq-article-excerpt">My first real encounter with structured query language, and why databases finally started making sense.</div>
        <span class="iq-article-tag">Data &amp; ML</span>
      </div>
    </a>

    <a class="iq-article-card" href="/posts/My-First-Project/">
      <img class="iq-article-thumb" src="https://images.pexels.com/photos/7988114/pexels-photo-7988114.jpeg?auto=compress&cs=tinysrgb&w=400" alt="" />
      <div class="iq-article-body">
        <div class="iq-article-date">June 02, 2026</div>
        <div class="iq-article-title">My ML Project: Combining Database, Visualization and Machine Learning</div>
        <div class="iq-article-excerpt">Tying it all together — a project that pulled in databases, data visualization, and a working ML model.</div>
        <span class="iq-article-tag">Data &amp; ML</span>
      </div>
    </a>

    <a class="iq-article-card" href="/posts/studying-Machine-Learning/">
      <img class="iq-article-thumb" src="https://images.pexels.com/photos/5483075/pexels-photo-5483075.jpeg?auto=compress&cs=tinysrgb&w=400" alt="" />
      <div class="iq-article-body">
        <div class="iq-article-date">June 25, 2026</div>
        <div class="iq-article-title">My First Experience with Machine Learning and Pandas</div>
        <div class="iq-article-excerpt">My most recent post — first real attempts at machine learning, with pandas doing the heavy lifting behind the scenes.</div>
        <span class="iq-article-tag">Data &amp; ML</span>
      </div>
    </a>

  </div>

</div>
