---
title : welcome to the blog
layout: layout.liquid
---

#welcome to the blog

{% for blog in collections.letuslearnEleventy %}

- [{{blog.data.title}}]({{blog.url}})
{% endfor  %}
you can read it sir
