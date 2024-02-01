---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

{% capture content %}
{% include figure.html image="images/frontier-hall.jpg" caption="Frontier Hall" %}
{% endcapture %}


{% include float.html content=content %}

{%
  include button.html
  type="email"
  text="timothy.sweeny@du.edu"
  link="timothy.sweeny@du.edu"
%}
{%
  include button.html
  type="phone"
  text="303-871-2191"
  link="+1-303-871-2191"
%}
{%
  include button.html
  type="address"
  text="Department of Psychology, Frontier Hall
2155 S. Race St.
Denver, CO 80208"
  link="https://www.google.com/maps"
%}

{% include float.html clear=true %}

{% include section.html %}
