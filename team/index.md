---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

# {% include icon.html icon="fa-solid fa-users" %}优秀毕业生

# {% include icon.html icon="fa-solid fa-users" %}学生

{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

{% include grid.html style="square" content=content %}
