---
title: Facilities
nav:
  order: 5
  tooltip: Lab pictures and tools
---

# {% include icon.html icon="fa-solid fa-photo-film" %}Facilities

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
  caption="Eyetracker"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
