---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% for post in site.publications reversed %}

**{{ post.title }}**  
{% if post.authors %}{{ post.authors }}  
{% endif %}{% if post.status %}{{ post.status }}{% endif %}{% if post.date %}{% if post.status %}, {% endif %}{{ post.date | date: "%Y" }}{% endif %}

{% endfor %}
