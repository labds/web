---
permalink: /people/

title:"Researchers"

gallery:
-url: /assets/images/hf.jpg
image_path:/assets/images/hf-th.jpg
alt: "hf"
title: "Hugo Figueiredo"
---

{% for staff_member in site.staff_members %}
  <h2>{{ staff_member.name }} - {{ staff_member.position }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}

