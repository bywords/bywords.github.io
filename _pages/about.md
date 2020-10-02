---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Postdoctoral Researcher at UCLA, working with [Dr. Jungseock Joo](http://jsjoo.com). Before joining UCLA, I was a postdoc at the Data Analytics group of Qatar Computing Research Institute. I received my Ph.D. from KAIST in 2018 with the honored dissertation with the guidance of [Dr. Meeyoung Cha](https://ds.ibs.re.kr/index.php/ci/).

My research area is **Data Science** using **Machine Learning**, and in particular, I am interested in understanding and tackling emerging social problems through online data. As a data scientist, my goal is to address the problems by advancing machine learning techniques on content and user behaviors. Recent interest focuses on detecting *online misinformation* and underlying *social bias* in online media through multi-modal cues such as image and text.

My research has made significant contributions to web-based data science and has been published in premier venues (*WWW'13*, *ICWSM'13*, *CIKM'15*, *CSCW'16*, *WWW'17*, *WWW'18*, *AAAI'19*, *ICWSM'20*, *ICWSM'21*). 

[[CV](/files/Kunwoo_CV.pdf)] 
[[Google Scholar](https://scholar.google.com/citations?user=xiZ1ImoAAAAJ)] 
[[Summary of a few research projects](https://bywords.github.io/research/)]




# News

{% for post in site.news reversed %}
  {% include archive-single-news.html %}
{% endfor %}
