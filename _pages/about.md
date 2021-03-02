---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an assistant professor at School of AI Convergence in Soongsil University.
Before joining Soongsil, I was a postdoc at UCLA and QCRI. I received my Ph.D. at KAIST in 2018 with the guidance of [Dr. Meeyoung Cha](https://ds.ibs.re.kr/index.php/ci/).

I am interested in tackling emerging social issues through analyzing online data and providing data-driven solutions for mitigating the problems. Recent interest focuses on **detecting** *misinformation* and *social bias* in online media platforms through multi-modal analyses, and **understanding** its effects on future *audience behaviors*. 
My technical expertise lies in **Data Science** and **Deep Learning**, and in particular, I have experiences in **Natural Language Processing** and **Causal Inference**.

My research has been published in premier computer science/interdisciplinary conferences (WWW, ICWSM, CIKM, CSCW, AAAI) and journals (JA, IEEE Access). 
 
You can check my previous research records and details in the following:

[[CV](/files/Kunwoo_CV.pdf)]
[[Google Scholar](https://scholar.google.com/citations?user=xiZ1ImoAAAAJ)] 
[[Research Summary](https://bywords.github.io/research/)]




# News

{% for post in site.news reversed %}
  {% include archive-single-news.html %}
{% endfor %}
