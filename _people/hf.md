---
name: Hugo Figueiredo

position: Researcher
---

Hugo launched LAB-DS in 2019.

{% for staff_member in site.staff_members %}
  <h2>{{ staff_member.name }} - {{ staff_member.position }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
