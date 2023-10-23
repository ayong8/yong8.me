---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% include base_path %}

{% for post in site.talks reversed %}
  {% include archive-single-news.html %}
{% endfor %}
