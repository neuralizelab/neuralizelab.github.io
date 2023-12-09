---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team is the cornerstone of our lab, consisting of qualified AI researcher, data scientist, entrepreneur and innovative engineer from diverse backgrounds. Each member brings a unique blend of expertise in various domains, from machine learning to full stack web development. Our collaborative spirit and commitment drive the lab's success. Together, we strive to create AI solutions that are not only technologically advanced but also socially responsible and impactful.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}
