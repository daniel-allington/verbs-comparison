---
layout: default
---

<ul>
{% for lemma in site.lemmas %}
    <li><a href = "{{ lemma.url }}">{{ lemma.lemma }}</a></li>
{% endfor %}
</ul>
