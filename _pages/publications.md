---
layout: archive
title: ""
permalink: /publications/
author_profile: true
entries_layout: grid
---

# How prior knowledge of statistical regularities influence cognition

 {% include base_path %}

 {% for post in site.publications reversed %}
  {% if post.pub == 0 %}
     {% include archive-single.html %}
  {% endif %}
 {% endfor %}

---

# Neural and behavioral dynamics of complex cognitive functions

{% for post in site.publications reversed %}
  {% if post.pub == 1 %}
     {% include archive-single.html %}
  {% endif %}
{% endfor %}

---

# Others
{% for post in site.publications reversed %}
  {% if post.pub == 2 %}
     {% include archive-single.html %}
  {% endif %}
{% endfor %}
