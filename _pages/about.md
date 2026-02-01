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

* **Ph.D. in Computer Science** | *National University of Singapore* | 2020 – 2025
  * Dissertation: *Improving Super-Resolution Methods for
Real-World Requirements*
  * Advisor: Prof. Angela Yao

* **B.Sc. in Computer Science and Technology** | *Huazhong University of Science and Technology, China* | 2016 – 2020


## Selected Publications

{% for post in site.publications reversed limit:3 %}
  {% include archive-single.html type="list" %}
{% endfor %}

<br>
[View all publications](/publications/){: .btn .btn--info}

<style>
  /* Shrink the title font and details */
  .archive__item-title {
    font-size: 0.95em !important;
    margin-top: 0 !important;
  }
  .archive__item-excerpt {
    font-size: 0.85em !important;
    line-height: 1.4;
  }
  /* Ensure the thumbnail is a small square on the left */
  .list__item .archive__item-teaser {
    max-width: 100px;
    float: left;
    margin-right: 20px;
  }
  /* Clear the float so the button doesn't overlap */
  .list__item {
    clear: both;
    margin-bottom: 20px;
    border-bottom: 1px solid #f2f2f2;
    padding-bottom: 10px;
  }
</style>