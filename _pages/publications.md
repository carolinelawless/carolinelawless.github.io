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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* Lawless, Robert, Rousseau, Ryder (2023+)
**Asymptotics of approximate Bayesian computation when summary statistics converge at heterogeneous rates**, ([Arxiv](https://arxiv.org/abs/2311.10080)).

* Lawless, Alamichel, Arbel, Kon Kam King (2023)
**Clustering consistency with Dirichlet process mixtures.**
*Biometrika*, 110(2), 551-558 ([pdf](https://arxiv.org/abs/2205.12924)).

* Ascolani, F., Lijoi, A. and Ruggiero, M. (2023)
**Smoothing distributions for conditional Fleming--Viot and Dawson--Watanabe diffusions.**
*Bernoulli*, 29(2): 1410-1434 ([pdf](https://arxiv.org/abs/2204.12738)).
