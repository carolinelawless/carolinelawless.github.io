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

* Lawless, C., Robert, J., Rousseau , J., Ryder, R. (2023+)
**Asymptotics of approximate Bayesian computation when summary statistics converge at heterogeneous rates**
([arXiv](https://arxiv.org/abs/2311.10080))

* Lawless, C., Alamichel L., Arbel, J., Kon Kam King, G. (2023)
**Clustering inconsistency for Pitman--Yor mixture models with a prior on the precision but fixed discount parameter**
*Fifth Symposium on Advances in Approximate Bayesian Inference* ([http](https://openreview.net/forum?id=r9CvCsfkfPW))

* Lawless, C., Arbel, J. (2019)
**A simple proof of Pitman--Yor's Chinese restaurant process from its stick-breaking representation**
*Dependence Modeling* ([HAL](https://hal.science/hal-01950653))






{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
