---
title: Team
nav:
  order: 1
  tooltip: Our Team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our research team is composed of five faculty members specializing in Statistics and Data Sciences from the Department of Mathematical Sciences at The University of Texas at Dallas, along with a group of dedicated PhD students.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Our research team is composed of five faculty members specializing in Statistics and Data Sciences from the Department of Mathematical Sciences at The University of Texas at Dallas, along with a group of dedicated PhD students.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/jiayi.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
