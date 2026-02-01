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
{% assign sorted_pubs = site.publications | sort: 'weight' %}
{% for post in site.publications reversed limit:3 %}
  {% include archive-single.html type="list" %}
{% endfor %}

<br>
[View all publications](/publications/){: .btn .btn--info}

<style>
  /* Flexbox layout for the list item */
  .list__item {
    display: flex;
    align-items: flex-start;
    margin-bottom: 30px;
    border-bottom: 1px solid #eee;
    padding-bottom: 15px;
  }

  /* Style the thumbnail */
  .archive__item-teaser {
    flex: 0 0 120px; /* Fixed width for image */
    margin-right: 20px;
    overflow: hidden;
    border-radius: 4px;
  }

  /* Shrink text font */
  .archive__item-title {
    font-size: 1.0rem !important;
    margin-bottom: 5px !important;
  }

  .archive__item-excerpt {
    font-size: 0.85rem !important;
    color: #666;
  }
</style>