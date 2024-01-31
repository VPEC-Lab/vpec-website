---
title: Team
nav:
  order: 5
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: grad" %}
{% include list.html data="members" component="portrait" filters="role: gres" %}
{% include list.html data="members" component="portrait" filters="role: ug" %}
{% include list.html data="members" component="portrait" filters="role: dog" %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

{% include list.html data="members" component="portrait" filters="role: alum" %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
