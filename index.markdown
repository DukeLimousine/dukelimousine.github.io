---
layout: default
title: High Council Home
permalink: /
---

<div class="image-wrapper">
  <img src="assets/images/logo.png" alt="High Council Logo" class="logo">
</div>

<div class="button-container">
  {% for link in site.data.links.links %}
    <a href="{{ link.href }}" class="button-style">{{ link.text }}</a>
  {% endfor %}
</div>

