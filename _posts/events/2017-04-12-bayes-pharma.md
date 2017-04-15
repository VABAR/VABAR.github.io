---
layout: page
title: "Bayes-Pharma 2017"
subheadline: "Albacete, 22-25 May 2017"
meta_teaser: "VaBaR course: Introduction to Bayesian Survival Models"
teaser: "VaBaR course: Introduction to Bayesian Survival Models"
header: no
image:
    title: header_bayes-pharma.png
    caption: "http://www.bayes-pharma.org/"
    caption_url: http://www.bayes-pharma.org/
    homepage: homepage_bayes-pharma.png
    thumb: thumb_bayes-pharma.png
categories: events
---

The Bayes Pharma conference focus on Bayesian approaches in pharmaceutical research.

Co-organized by [VaBaR member](/members/) [Virgilio Gómez-Rubio](http://www.uclm.es/profesorado/vgomez/), this year's edition features a short course on __Bayesian Survival Models__ by 

{% for member in site.data.members %}
  {% if member.name == "Carmen Armero" or member.name == "Danilo Alvares" or member.name == "Elena Lázaro" %}
<div class="row">
  <div class="small-2 columns">
    <img src="{{ site.url }}/images/members/{{ member.img }}">
  </div>
  <div class="small-10 columns">
    <a href="{{ member.url }}">
      {{ member.name }}
    </a> <br />
    Universitat de València, Spain
  </div>
</div><!-- /.row -->
  {% endif %}
{% endfor %}


Survival analysis is one of the most important areas of applied and theoretical research in Statistics, with many important contributions in life sciences. This small course focuses on Bayesian reasoning in survival models. It contains the most basic elements and procedures in the subject without a strong theoretical approach but a conceptual and applied perspective that enables comprehensive modeling. Topics will be illustrated by means of real studies
that will be subsequently worked with more depth in practical sessions.

## Programme

1. Introduction.

2. Basic statistical concepts: survival function, hazard rate, censoring and truncation.

3. Time-to-event regression models: accelerated failure models and proportional hazards (Cox) models.

4. Frailty models.

5. Cure rate models.

6. Joint models of longitudinal and survival data.


## Bibliography

__R. Christensen, W.O. Johnson, A. J. Branscum and T. E. Hanson (2011)__. _Bayesian Ideas and Data Analysis_. Boca Raton: Chapman and Hall.

__J. G. Ibrahim, M.-H. Chen, and D. Sinha (2001)__. _Bayesian Survival Analysis_. New York: Springer

__J. P. Klein and M. L. Moeschberger (2003)__. _Survival Analysis: Techniques for Censored and Truncated Data_. Second Edition. New York: Springer-Verlag