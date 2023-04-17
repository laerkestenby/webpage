---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of [Steno Diabetes Center Aarhus](https://www.stenoaarhus.dk/) and affiliated with the [Department of Public Health, Aarhus University](https://ph.au.dk/). We are located on the 3rd & 4th floors of the Forum building at Aarhus University Hospital.

Subscribe to our [newsletter](https://mailchi.mp/rm/hulman-lab-newsletter) to get notified about job openings, or contact Adam if you are interested in joining our research group or collaborating with us. We also welcome foreign researchers for shorter visits with several funding options.

{%
  include button.html
  type="email"
  text="adahul@rm.dk"
  link="adahul@rm.dk"
%}
{%
  include button.html
  type="phone"
  text="(+45) 23 70 74 81"
  link="+45-23707481"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/zRXmXWTvNAdV4iF59"
%}
{%
  include button.html
  type="newsletter"
  text="Subscribe to our Newsletter"
  link="https://mailchi.mp/rm/hulman-lab-newsletter"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
