---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## **Refereed Journal Publications**

<b>Centrifuge-based step emulsification device for simple and fast generation of monodisperse picoliter droplets</b> <br>
<b>Dong-Chel Shin</b>, Yuya Morimoto, Jun Sawayama, Shigenori Miura, and Shoji Takeuchi* <br>
<i>Sensors & Actuators: B. Chemical</i> (IF = 7.100, [Link](https://www.sciencedirect.com/science/article/pii/S0925400519313632))

## **International Conference Presentations**

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
