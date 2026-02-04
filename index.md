---
layout: default
title: Home
---

# Hsin-Pei Chen (陳昕霈)
**PhD Student in Astronomy and Astrophysics | UT Austin**

---

## About Me
I am a PhD student at the University of Texas at Austin's Department of Astronomy. My academic background includes a Master's degree in Astronomy. 

## Research Interests
My professional focus is centered on several key areas in Astrophysics:
* **Supernovae**
* **Star Formation**
* **Transients**

---

## Recent Updates & Blog
{% for post in site.posts limit:10 %}
* **[{{ post.date | date: "%Y-%m-%d" }}] [{{ post.title }}]({{ post.url }})**
{% endfor %}

---

### Contact Information
* **Email**: hpchen@utexas.edu
* **Location**: Austin, Texas
