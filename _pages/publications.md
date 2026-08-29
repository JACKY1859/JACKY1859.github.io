---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

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
