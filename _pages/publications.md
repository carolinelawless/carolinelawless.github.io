---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

* Lawless, C., Robert, J., Rousseau , J. and Ryder, R. (2023+)
**Asymptotics of approximate Bayesian computation when summary statistics converge at heterogeneous rates.**
([arXiv](https://arxiv.org/abs/2311.10080)).




{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
