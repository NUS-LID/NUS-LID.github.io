---
title: Home
---

{% include figure.html image="images/logo.png" width="400px" %}

This website is currently under construction.

Welcome to the Learning and Reasoning Agent group (LRA) at NUS. We work on learning and reasoning agents, including machine learning, planning under uncertainty, and approximate inference.

{% include section.html %}

## Highlights

{% capture text %}

Explore our highlighted research papers. Members can add project pages following the Shell Game example on the Research page.

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
  image="images/logo.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Meet our current team members and alumni.

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
  flip=true
  text=text
%}
