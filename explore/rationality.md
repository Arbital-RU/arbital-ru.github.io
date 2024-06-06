---
layout: page
permalink: /explore/rationality
title: Рациональность
excerpt: "Рациональность"
---
{% include domains.html domain = "rationality" %}

<ul class="tree" style="margin-left: -1.5rem">
{% for a in site.data.p %}
  {% if a.id == "rationality" %}
  <li><details open>
  <summary>{% include post.html id = a.id %}</summary>
  {% include list.html list = a.children %}
  </details></li>{% break %}
  {% endif %}
{% endfor %}
</ul>
