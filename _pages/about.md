---
permalink: /
title: "About"
excerpt: "Assistant Professor of Information Technology and Business Analytics at NC State University."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an Assistant Professor of Information Technology and Business Analytics in the [Department of Information Technology, Analytics & Operations](https://poole.ncsu.edu/faculty-and-research/it-analytics-operations-department/) at Poole College of Management, NC State University. I received my Ph.D. degree in Management Science from the University of Texas at Dallas.

My research focuses on the economic impact of technologies and examines how emerging technologies shape individual behavior and firm performance across various contexts, including crowdsourcing, online labor markets, digital platforms, and social media. Methodologically, I draw on a broad range of approaches, including econometrics, design science, machine learning, experiments, and surveys. Through my research, I aim to generate managerial insights that help individuals and organizations make better decisions and improve performance.

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
  <p>“A Recommendation Framework for Crowdsourcing Contest Design,” with Zhu, W., Menon, Y., and Sarkar, S.</p>
</div>

<div class="publication-list__item">
  <p>“Follow the Standard or Name Its Own Prize? An Empirical Study of Prize Strategies and Contest Success in Crowdsourcing,” with Wang, Y., Wang, L., and Chen, J.</p>
</div>

## Contact

[jhmo3@ncsu.edu](mailto:jhmo3@ncsu.edu)
