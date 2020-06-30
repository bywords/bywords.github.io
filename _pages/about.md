---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Postdoctoral Researcher in UCLA, working with [Dr. Jungseock Joo](http://jsjoo.com). 

My research interest lies in **understanding and tackling emerging social phenomena using data science methods**: so-called *Computational Social Science*. I have mostly analyzed the data of online news and social media through machine learning on text.
Recent interest focuses on **online misinformation and bias through the lens of multimedia**, such as image and text. I hope my research efforts can contribute to making the polarized world a better place!

I received my Ph.D. from KAIST at 2018 with the honored dissertation with the guidance of [Dr. Meeyoung Cha](https://ds.ibs.re.kr/index.php/ci/). 
I have published studies at computer science or interdisciplinary conferences, such as WWW, AAAI, CSCW, and ICWSM.

Please check the full list of publication records in my [CV](/files/kunwoo-cv.pdf) or the [Google Scholar profile](https://scholar.google.com/citations?user=xiZ1ImoAAAAJ).




# News

{% for post in site.news reversed %}
  {% include archive-single-news.html %}
{% endfor %}
