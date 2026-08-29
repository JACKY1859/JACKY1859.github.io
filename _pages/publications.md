---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

<h2>Research Papers</h2>

<ol>
{% for post in site.publications reversed %}
  <li style="margin-bottom: 1.2em;">
    <strong>{{ post.title }}</strong><br>
    {% if post.authors %}{{ post.authors }}.{% endif %}
    {% if post.status %} {{ post.status }},{% endif %}
    {% if post.date %} {{ post.date | date: "%Y" }}.{% endif %}
  </li>
{% endfor %}
</ol>

<h2>Interdisciplinary Research</h2>

<ol>
  <li style="margin-bottom: 1.2em;">
    <strong>Chattering Phenomena in Time-Optimal Control for High-Order Chain-of-Integrator Systems With Full State Constraints</strong><br>
    Yunan Wang, Chuxiong Hu, Zeyang Li, <strong>Yujie Lin</strong>, Shize Lin, and Suqin He.<br>
    <em>IEEE Transactions on Automatic Control</em>, 2025.
  </li>

  <li style="margin-bottom: 1.2em;">
    <strong>A Novel State-Centric Necessary Condition for Time-Optimal Control of Controllable Linear Systems Based on Augmented Switching Laws</strong><br>
    Yunan Wang, Chuxiong Hu, <strong>Yujie Lin</strong>, Zeyang Li, Shize Lin, and Suqin He.<br>
    <em>IEEE Transactions on Automatic Control</em>, 2025.
  </li>
</ol>

<h2>Expository Writings</h2>

<ol>
  <li style="margin-bottom: 1.2em;">
    <strong>K3曲面微分同胚群的代数与拓扑结构</strong><br>
    Undergraduate thesis, 2023.
  </li>

  <li style="margin-bottom: 1.2em;">
    <strong>Seiberg–Witten Invariants of Symplectic Manifolds</strong><br>
    Expository notes, 2023.
  </li>
</ol>
