---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and group == 'team'" %}


## Alumni

{% include list.html  data="members"  component="portrait"  filter="group == 'alumni'" %}

{% include section.html %}

Please reach out if you are interested in joining.
