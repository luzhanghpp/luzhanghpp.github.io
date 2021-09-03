---
layout: default
title: "Others"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
