---
title: Activities
nav:
  order: 4
  tooltip: recent updates, articles and posts
---

# <i class="fas fa-feather-alt"></i> Lab Activities

{% include section.html %}

{% capture text %}

Abcdef

[Meet our team &nbsp;→](team)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/teamcb.png"
  link="team"
  headline="Our Team"
  text=text
%}

{% capture col1 %}
{%
  include figure.html
  image="images/teamcb.png"
  caption="Khattri Lab Group Dinner [21.08.23]"
%}
{% endcapture %}

{% capture col1 %}
{%
  include figure.html
  image="images/fidka.jpeg"
  caption="Khattri Lab Group Dinner [01.05.24]"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/fidkas.jpeg"
  caption="Khattri Lab Farewell [01.05.24]"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}

{% include search-info.html %}



{% include section.html %}
