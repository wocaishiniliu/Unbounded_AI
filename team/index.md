---
title: Team
nav:
  order: 15
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are more than just a lab; we are a community of curious minds. Our strength comes from our diversity, and we actively foster a supportive space where everyone feels a sense of belonging. We believe that celebrating our different experiences and perspectives makes our science better. Our team proudly includes researchers at every stage of their career, from undergraduates to postdocs, all contributing to our shared mission

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Collaboration is at the heart of everything we do. We thrive on partnering with exceptional teams from across the globe, believing that a fusion of unique perspectives is the key to real breakthroughs. Together, we aim to solve critical challenges in data science while mentoring the talented researchers who will lead the field tomorrow. We are always open to new ideas and new partners.

{% include section.html %}

<!-- {% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %} -->

{% include grid.html style="square" content=content %}
