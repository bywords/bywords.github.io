---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a postdoctoral researcher at UCLA, working with [Dr. Jungseock Joo](http://jsjoo.com).
Before joining UCLA, I was also a postdoc at Qatar Computing Research Institute. I received my Ph.D. from KAIST in 2018 with the honored dissertation with the guidance of [Dr. Meeyoung Cha](https://ds.ibs.re.kr/index.php/ci/).

I am interested in tackling emerging social issues through analyzing online data and providing data-driven solutions for the mitigating the problems. Recent interest focuses on **detecting** *misinformation* and *social bias* in online media platforms, and **understanding** its effects on future audience behaviors. 

My technical expertise lies in **Data Science** and **Machine Learning**, and in particular, I am interested in **Deep Learning on Text** and **Causal Inference**.

My research has been published in premier computer science/interdisciplinary conferences (WWW, ICWSM, CIKM, CSCW, AAAI) and journals (JA). 
 
You can check my previous research records and details in the following:

[[CV](/files/Kunwoo_CV.pdf)]
[[Google Scholar](https://scholar.google.com/citations?user=xiZ1ImoAAAAJ)] 
[[Research Summary](https://bywords.github.io/research/)]




# News

{% for post in site.news reversed %}
  {% include archive-single-news.html %}
{% endfor %}
