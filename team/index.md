---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and group == 'team'" %}


## Alumni

{% include list.html  data="members"  component="portrait"  filter="group == 'alumni'" %}

{% include section.html %}

Please reach out if you are interested in joining.

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}