---
layout: page
permalink: /explore/ai_alignment
title: Согласование ИИ
excerpt: "Согласование ИИ"
---
{% include domains.html domain = "AI" %}

<a name="Полное_дерево"></a>

<table style="border: none; margin: 8px 0 8px 0; background-color: white"><tr style="margin: 0; padding: 0">
  <td style="border: none; background-color: white; margin: 0; padding: 0">
    <h3>Полное дерево:</h3>
  </td>
  <td style="float: right; border: none; background-color: white; margin: 0; padding: 0; white-space: nowrap">
    <h3><a href="#Только_переводы">↓ Только переводы</a></h3>
  </td>
</tr></table>

<ul class="tree" style="margin-left: -1.5rem">
{% for a in site.data.p %}
  {% if a.id == "ai_alignment" %}
  <li><details open>
  <summary>{% include post.html id = a.id %}</summary>
  {% include list.html list = a.children %}
  </details></li>{% break %}
  {% endif %}
{% endfor %}
</ul>

---
<a name="Только_переводы"></a>

<table style="border: none; margin: 8px 0 8px 0; background-color: white"><tr style="margin: 0; padding: 0">
  <td style="border: none; background-color: white; margin: 0; padding: 0">
    <h3>Только переводы:</h3>
  </td>
  <td style="float: right; border: none; background-color: white; margin: 0; padding: 0; white-space: nowrap">
    <h3><a href="#Полное_дерево">↑ Полное дерево</a></h3>
  </td>
</tr></table>

<ul>
{% for a in site.data.p %}
{% if a.domains contains "ai_alignment" and a.translated %}
  <li>{% include post.html id = a.id %}</li>
{% endif %}
{% endfor %}
</ul>

<!--
---
**Не будет переводиться:**
<ul>
{% for a in site.data.p %}
{% if a.domains contains "ai_alignment" and a.deleted %}
  <li>{% include post.html id = a.id %}</li>
{% endif %}
{% endfor %}
</ul>
-->
