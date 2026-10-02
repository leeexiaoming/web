---
permalink: /research/
title: "Research"
author_profile: true
---

My research focuses on the design and consequences of digital platforms. I investigate how platform features, information, incentives, and emerging technologies influence participation, performance, and welfare.

I combine **applied econometrics**, **experiments**, **machine learning**, **large language models**, **text mining**, and **image analysis** in my work.

My current interests include:

- Digital platforms and online marketplaces
- Open innovation and crowdsourcing contests
- Online labor markets testing case
- Social media advertising and online communities
- AI-enabled services and human–AI interaction

## Selected Publications

{% for post in site.publications reversed %}
<div class="publication-list__item">
  <p>
    {{ post.citation }} (UTD24, FT50)<br />
    {% if post.paperurl %}<a href="{{ post.paperurl }}">View Paper</a>{% endif %}
  </p>
</div>
{% endfor %}

## Working Papers

<div class="publication-list__item">
  <p>Wangsheng Zhu, Jiahui Mo, Syam Menon, and Sumit Sarkar. “A Recommendation Framework for Crowdsourcing Contest Design.”</p>
</div>

<div class="publication-list__item">
  <p>Yuying Wang, Jiahui Mo, Le Wang, and Jianqing Chen. “Follow the Standard or Name Its Own Prize? An Empirical Study of Prize Strategies and Contest Success in Crowdsourcing.”</p>
</div>
