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

<h2>Expository Notes</h2>

<ol>
  <li style="margin-bottom: 1.2em;">
    <strong>Inflation Techniques in Symplectic 4-Manifolds</strong><br>
    Expository notes, 2026.
  </li>

  <li style="margin-bottom: 1.2em;">
    <strong>An Introduction to Seiberg–Witten Theory</strong><br>
    Expository notes, 2025.
  </li>
</ol>
