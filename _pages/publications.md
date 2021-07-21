---
layout: archive
title: "Refereed Journal Publications"
permalink: /publications/
author_profile: true
---
<b>[Centrifuge-based step emulsification device for simple and fast generation of monodisperse picoliter droplets](https://www.sciencedirect.com/science/article/pii/S0925400519313632)</b> <br>
<b>Dong-Chel Shin</b>, Yuya Morimoto, Jun Sawayama, Shigenori Miura, and Shoji Takeuchi*, <i>Sensors & Actuators: B. Chemical</i> (IF = 7.100)

---
layout: archive
title: "International Conference Presentations"
permalink: /publications/
author_profile: true
---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
