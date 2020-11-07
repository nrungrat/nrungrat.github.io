---
layout: archive
title: ""
permalink: /publications/
author_profile: true
entries_layout: grid
---

# Pre-prints:

 {% include base_path %}

 {% for post in site.publications reversed %}
  {% if post.pub == 0 %}
     {% include archive-single.html %}
  {% endif %}
 {% endfor %}

---

# Articles:

{% for post in site.publications reversed %}
  {% if post.pub == 1 %}
     {% include archive-single.html %}
  {% endif %}
{% endfor %}

---

# Dissertation and Theses:
{% for post in site.publications reversed %}
  {% if post.pub == 2 %}
     {% include archive-single.html %}
  {% endif %}
{% endfor %}
