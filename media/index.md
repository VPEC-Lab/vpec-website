---
title: Media
nav:
  order: 4
  tooltip: Lab pictures and events
---

# {% include icon.html icon="fa-solid fa-photo-film" %}Media

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Our Lab"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Community Outreach"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
