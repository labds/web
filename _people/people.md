---
permalink: /people/
title: "People"
gallery:
  - url: /assets/images/hf.jpg
    image_path: /assets/images/hf-th.jpg
    alt: "hugo figueiredo" 
---


{% for staff_member in site.staff_members %}
  <h2>{{ staff_member.name }} - {{ staff_member.position }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
