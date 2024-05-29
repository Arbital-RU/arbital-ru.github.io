---
layout: page
permalink: /explore/decision_theory
title: Теория принятия решений
excerpt: "Теория принятия решений"
---
{% include domains.html domain = "decision_theory" %}

<ul class="tree" style="margin-left: -1.5rem">
{% for a in site.data.p %}
  {% if a.id == "decision_theory" %}
  <li><details open>
  <summary>{% include post.html id = a.id %}</summary>
  {% include list.html list = a.children %}
  </details></li>{% break %}
  {% endif %}
{% endfor %}
</ul>
