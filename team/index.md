---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab shares the passion for data science and a thrive to make a difference for people with diabetes. We come from diverse backgrounds (data science, engineering, epidemiology, mathematics, medicine, sport science) and enjoy collaborations across disciplines. We aim to create a professional working environment that embraces our differences, encourages out-of-the-box thinking, and where there is a place for the famous Danish ‘hygge’.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

Subscribe to our newsletter to hear among the first ones about job opening, contact Adam if you are interested in joining us or collaborating with us.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/adam-hulman.jpg" %}
{% include figure.html image="images/manuel-thomasen.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
