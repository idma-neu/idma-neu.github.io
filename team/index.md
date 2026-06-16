---
title: 团队介绍
nav:
  order: 3
  tooltip: 关于我们
---

# {% include icon.html icon="fa-solid fa-users" %}指导教师

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

# {% include icon.html icon="fa-solid fa-users" %}合作导师

{% include list.html data="members" component="portrait" filter="role == 'cooperative-investigator'" %}

# {% include icon.html icon="fa-solid fa-users" %}博士毕业生

{% include list.html data="members" component="portrait" filter="role == 'phdFinished'" %}

# {% include icon.html icon="fa-solid fa-users" %}博士研究生

{% include list.html data="members" component="portrait" filter="role == 'phd2020'" %}

{% include list.html data="members" component="portrait" filter="role == 'phd2022'" %}

{% include list.html data="members" component="portrait" filter="role == 'phd2023'" %}

{% include list.html data="members" component="portrait" filter="role == 'phd2024'" %}

{% include list.html data="members" component="portrait" filter="role == 'phd2025'" %}


# {% include icon.html icon="fa-solid fa-users" %}硕士研究生

{% include list.html data="members" component="portrait" filter="role == 'master2023'" %}

{% include list.html data="members" component="portrait" filter="role == 'master2024'" %}

{% include list.html data="members" component="portrait" filter="role == 'master2025'" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-briefcase" %}硕士毕业生去向

{% assign master_by_year = site.data.alumni | where_exp: "item", "item.degree == '硕士'" | group_by_exp: "item", "item.date | date: '%Y'" | sort: "name" | reverse %}
{% for year_group in master_by_year %}
{% if year_group.name and year_group.name != "" %}
### {{ year_group.name }}年毕业生
{% endif %}
{% assign sorted = year_group.items | sort: "order" %}
{% for person in sorted %}
{% assign dest_type = site.data.types[person.destination_type] %}
- **{{ person.name }}**{% if person.destination %}：{{ person.destination }}{% if dest_type %} {% include icon.html icon=dest_type.icon %}{% endif %}{% endif %}
{% endfor %}
{% endfor %}
