---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Zhang Yuehan, a researcher at the Graphics & Image Intelligence Lab, Huawei Singapore Research Center. Previously, I obtained my Ph.D degree from National University of Singapore, supervised by Associate Professor Angela Yao. Before that, I got my Bachelor degree from Huazhong University of Science and Technology. My research focused on sovling the most challenging problems in the low-level vision, including solving the confilicts between regression and generation and achieving stable video/image super-resolution performance in changing real-world conditions. Now I am exploring on image/video generation tasks, specifically, how to measure the generation quality and give effective rewards.


## Selected Publications

{% for post in site.publications reversed limit:3 %}
  {% include archive-single.html %}
{% endfor %}

[View all publications](/publications/){: .btn .btn--info}
