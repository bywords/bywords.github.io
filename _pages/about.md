---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Postdoctoral Researcher at UCLA, working with [Dr. Jungseock Joo](http://jsjoo.com). Before joining UCLA, I was a postdoc at the Data Analytics group of Qatar Computing Research Institute, and I received my Ph.D. from KAIST in 2018 with the honored dissertation with the guidance of [Dr. Meeyoung Cha](https://ds.ibs.re.kr/index.php/ci/).

My research area is **Applied Data Science for Social Good**. In particular, I am interested in understanding and tackling emerging social problems through online data, and my goal as a data scientist is to address the problems through machine learning techniques on content and user behaviors. Recent interest focuses on developing graph neural network methods for detecting online misinformation and social bias through multi-modal content such as image and text.

Please check the full list of publication records in my [CV](/files/Kunwoo_CV.pdf) or the [Google Scholar profile](https://scholar.google.com/citations?user=xiZ1ImoAAAAJ). A summary of the three projects is available at this [page](https://bywords.github.io/research/).




# News

{% for post in site.news reversed %}
  {% include archive-single-news.html %}
{% endfor %}
