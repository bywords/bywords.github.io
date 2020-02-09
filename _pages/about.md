---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am Kunwoo Park, a PostDoc in UCLA Communication. I study at the intersection of Data science/AI approaches and social science, known as Computational Social Science. Recent research interest is online misinformation and fake news, which is a significant problem that not only reduces the probability of long-term usage in online systems but also undermines the credibility of our society.

I am open to chat with collaboration and future job opportunities. Feel free to contact me if you are interested. [[CV]](/files/kunwoo-cv.pdf)

# News

{% for post in site.news reversed %}
  {% include archive-single-news.html %}
{% endfor %}
