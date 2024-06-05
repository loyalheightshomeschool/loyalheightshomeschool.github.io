---
title: Meet Our Teachers
---
{% for teacher in site.data.teachers %}{% if teacher.active == "t" %}

## {{ teacher.name }}

*Classes taught include: {{ teacher.classes }}*

{{ teacher.biography }}

---
{% endif %}{% endfor %}
