---
layout: archive
title: "Project"
permalink: /project/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
title: "Project:Threshold ARMA Model"
collection: Project
permalink: /project/timeseries
excerpt: 'Team: Yongjian Zheng, Yongkang Yang, Wenzhe Zhou, Xiaoran Yu'
date: 2023-1-19
paperurl: 'http://cokezyj.github.io/assets/TimeSeries_Analysis_Porject.pdf'
---

This paper is a reproduction of Threshold ARMA model and its application in financial data. 

[Download project here](http://cokezyj.github.io/assets/TimeSeries_Analysis_Porject.pdf)
