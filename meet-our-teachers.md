---
title: Meet Our Teachers
---
{% for teacher in site.data.teachers %}

## {{ teacher.name }}

*Classes taught include: {{ teacher.classes }}*

{{ teacher.biography }}

---

{% endfor %}