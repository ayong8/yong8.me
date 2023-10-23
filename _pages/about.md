---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! my name is Yongsu Ahn. I’m a final year PhD Student in School of Computing and Information at University of Pittsburgh. I’m luckily advised by Dr. Yu-Ru Lin at PICSO Lab.

My research interest broadly lies in human-centered responsible AI, at the intersection of Visual analytics, Fair and Explainable AI, and Interactive machine learning. I’m studying how AI-based tools will better assist the important decision makings and information use in our society. For the heterogenous population users including data practioners, domain experts and lay users, I pursue AI for everyone to develop and promote human-centered AI that is fair, interpretable, and responsible as a viable tool.

<h2>News</h2>
<table class="news-table">
  {% for post in site.news reversed %}
    {% include archive-single-news.html %}
  {% endfor %}
</table>

<h2>Publications</h2>
{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}