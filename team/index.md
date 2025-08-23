---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

{% include section.html background="images/background.jpg" dark=true %}

# {% include icon.html icon="fa-solid fa-users" %}学生

{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

{% include grid.html style="square" content=content %}
