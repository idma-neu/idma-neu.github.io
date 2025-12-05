---
title: 科研项目
nav:
  order: 2
  tooltip: 科研项目
---

# {% include icon.html icon="fa-solid fa-wrench" %}科研项目（国家级在研）

{% include section.html %}

{% include list.html data="projects" component="post-excerpt" filter="role == 'project-doing'" dense=true suppress_dates=true %}

# {% include icon.html icon="fa-solid fa-wrench" %}科研项目（国家级已结题）

{% include list.html data="projects" component="post-excerpt" filter="role == 'project-finished'" dense=true suppress_dates=true %}
