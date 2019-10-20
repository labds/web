---
permalink: /people/

title:"Researchers"
---

{% for people in site.people %}
  <h2>{{ people.name }} - {{ people.position }}</h2>
  <p>{{ people.content | markdownify }}</p>
{% endfor %}

