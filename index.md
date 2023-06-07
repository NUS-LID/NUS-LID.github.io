---
title: Home
---

<center> <font size='7'><b>NUS-LID Group</b></font> </center>

<center><font size="6"> <b>L</b>earning, <b>I</b>nference, and <b>D</b>ecision Group at NUS </font></center>


Welcome to NUS-LID group's website. We work on exciting research in machine learning, planning under uncertainty, and approximate inference. 

{% include section.html %}

## Highlights

{% capture text %}

Find out our selected research papers in the related fields of machine learning, planning, inference, and more. 

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Find out our current research topics!

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Meet with our team members

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
