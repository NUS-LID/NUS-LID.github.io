---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our group is affiliated with the Department of Computer Science in the School of Computing, National University of Singapore. 

Address: <br>
School of Computing <br>
National University of Singapore <br>
13 Computing Drive <br>
Singapore 117417 <br>
Republic of Singapore <br>

Office: COM3 02-28 <br>
Phone: +65 6516 4526 <br>
Fax: +65 6779 4580 <br>

{%
  include button.html
  type="email"
  text="leews@comp.nus.edu.sg"
  link="leews@comp.nus.edu.sg"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/GZvwBbQ3StvyHy9q8"
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
