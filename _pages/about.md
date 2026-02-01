---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Zhang Yuehan, a researcher at the *Graphics & Image Intelligence Lab, Huawei Singapore Research Center*. Previously, I obtained my Ph.D degree from National University of Singapore, supervised by **Associate Professor Angela Yao**. 

## Research Interests
My research focused on sovling the most challenging problems in the low-level vision, including solving the confilicts between regression and generation and achieving stable video/image super-resolution performance in changing real-world conditions. 

Now I expand my explorations to image and video generation tasks, specifically, how to measure the generation quality and give effective rewards.


## Experience

* **AIGC Researcher** | *Huawei Singapore Research Center* | May 2025 – Present
  * Text-to-Video generation
  * Text-to-Image generation

---
## Education

* **Ph.D. in Computer Science** | *National University of Singapore, Singapore* | 2020 – 2025
  * Dissertation: *IMPROVING SUPER-RESOLUTION METHODS FOR
REAL-WORLD REQUIREMENTS*
  * Advisor: Prof. Angela Yao

* **B.Sc. in Computer Science and Technology** | *Huazhong University of Science and Technology, Wuhan, China* | 2016 – 2020


## Selected Publications

{% for post in site.publications reversed limit:3 %}
  {% include archive-single.html type="grid"%}
{% endfor %}

[View all publications](/publications/){: .btn .btn--info}
