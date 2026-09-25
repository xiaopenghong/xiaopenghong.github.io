---
permalink: /
layout: home
title: "Xiaopeng Hong | Computer Vision & Machine Learning"
excerpt: "Professor at Harbin Institute of Technology researching computer vision, multimodal learning, and continual learning."
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<div class="home-hero" id="biography">
  <div class="home-hero__copy">
    <span class="eyebrow">Harbin Institute of Technology · School of Computer Science and Technology</span>
    <h1>Xiaopeng Hong <span>洪晓鹏</span></h1>
    <p class="home-hero__role">Professor · PhD Supervisor</p>
    <p class="home-hero__intro">I am a Professor and PhD Supervisor at Harbin Institute of Technology, where I received my PhD in Computer Application and Technology in 2010. Previously, I held research positions at Xi’an Jiaotong University and the University of Oulu in Finland. I study how visual and multimodal systems perceive, adapt, and keep learning, with a focus on computer vision, multimodal learning, continual learning, visual surveillance, and subtle facial movement analysis.</p>
    <div class="hero-actions"><a class="action action--primary" href="/research/">Explore research <span aria-hidden="true">↗</span></a><a class="action action--quiet" href="/publications/">Publications <span aria-hidden="true">→</span></a></div>
    <div class="hero-links"><a href="https://homepage.hit.edu.cn/hongxiaopeng">HIT profile</a><a href="https://scholar.google.com/citations?user=x3X-qysAAAAJ&amp;hl=en">Google Scholar</a><a href="mailto:hongxiaopeng@ieee.org">Email</a></div>
  </div>
  <div class="home-hero__portrait"><img src="/files/xiaopeng-portrait-2026.jpg" alt="Portrait of Xiaopeng Hong"></div>
</div>

<section class="home-section" aria-labelledby="research-heading">
  <div class="section-heading"><div><span class="eyebrow">01 / Focus</span><h2 id="research-heading">Research directions</h2></div><a href="/research/">View research →</a></div>
  <div class="focus-grid">
    <a class="focus-card" href="/research/"><span class="focus-card__number">01</span><h3>Computer vision</h3><p>Understanding people and scenes through visual data, from facial behavior to crowd analysis.</p><span class="focus-card__arrow" aria-hidden="true">↗</span></a>
    <a class="focus-card" href="/research/"><span class="focus-card__number">02</span><h3>Multimodal learning</h3><p>Connecting signals and modalities to build more capable perception systems.</p><span class="focus-card__arrow" aria-hidden="true">↗</span></a>
    <a class="focus-card" href="/research/"><span class="focus-card__number">03</span><h3>Continual learning</h3><p>Helping models acquire new knowledge while retaining what they learned before.</p><span class="focus-card__arrow" aria-hidden="true">↗</span></a>
  </div>
</section>

<section class="home-section" id="news" aria-labelledby="news-heading">
  <div class="section-heading"><div><span class="eyebrow">02 / Updates</span><h2 id="news-heading">Latest news</h2></div></div>
  <ol class="news-list">
    {% for item in site.data.news %}
    <li class="news-item"><time>{{ item.date }}</time><p>{{ item.text }}</p></li>
    {% endfor %}
  </ol>
</section>

<section class="home-section" id="teaching" aria-labelledby="teaching-heading">
  <div class="section-heading"><div><span class="eyebrow">03 / Teaching</span><h2 id="teaching-heading">Selected courses</h2></div><a href="https://homepage.hit.edu.cn/hongxiaopeng">HIT profile ↗</a></div>
  <div class="teaching-grid">
    <article class="teaching-card"><span class="teaching-card__place">Harbin Institute of Technology</span><h3>Current teaching</h3><ul><li>Computer Graphics and Virtual Reality</li><li>Formal Languages and Automata</li></ul></article>
    <article class="teaching-card"><span class="teaching-card__place">Xi’an Jiaotong University</span><h3>Previous teaching</h3><ul><li>Data Analysis, Algorithms, and Applications</li><li>Cyber-Physical Systems</li></ul></article>
    <article class="teaching-card"><span class="teaching-card__place">University of Oulu</span><h3>Previous teaching</h3><ul><li>Deep Learning</li><li>Computer Graphics</li></ul></article>
  </div>
</section>

<section class="home-section home-section--last" aria-labelledby="connect-heading"><div class="section-heading"><div><span class="eyebrow">04 / Connect</span><h2 id="connect-heading">Let's connect</h2></div></div><div class="connect-panel"><p>For research collaborations, academic inquiries, or prospective students, get in touch.</p><a class="action action--primary" href="/contact/">Contact information <span aria-hidden="true">↗</span></a></div></section>
