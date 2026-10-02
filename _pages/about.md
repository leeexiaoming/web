---
permalink: /
title: "About"
excerpt: "Assistant Professor of Information Technology and Business Analytics at NC State University."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an Assistant Professor of Information Technology and Business Analytics in the [Department of Information Technology, Analytics & Operations](https://poole.ncsu.edu/academic-departments/information-technology-analytics-and-operations/) at NC State University's Poole College of Management.

My research focuses on the design and consequences of digital platforms. I investigate how platform features, information, incentives, and emerging technologies influence participation, performance, and welfare. I combine **applied econometrics**, **experiments**, **machine learning**, **large language models**, **text mining**, and **image analysis** in my work.

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
    {{ post.citation }}<br />
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

## Contact

[jhmo3@ncsu.edu](mailto:jhmo3@ncsu.edu)
