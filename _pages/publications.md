---
layout: archive
title: "Selected publications"
permalink: /publications/
author_profile: true
---

You can find the full list of my publications on <u><a href="https://scholar.google.com/citations?user=xiZ1ImoAAAAJ">my Google Scholar profile</a></u> or <u><a href="../files/kunwoo-cv.pdf">CV</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
