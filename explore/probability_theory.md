---
layout: page
permalink: /explore/probability_theory
title: Теория вероятностей
excerpt: "Теория вероятностей"
---
{% include domains.html domain = "probability_theory" %}

<ul class="tree" style="margin-left: -1.5rem">
{% for a in site.data.p %}
  {% if a.id == "probability_theory" %}
  <li><details open>
  <summary>{% include post.html id = a.id %}</summary>
  {% include list.html list = a.children %}
  </details></li>{% break %}
  {% endif %}
{% endfor %}
</ul>
