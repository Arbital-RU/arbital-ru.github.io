---
layout: page
permalink: /explore/ai_alignment
title: Согласование ИИ
excerpt: ""
---
<ul class="tree" style="margin-left: -1.5rem">{% for a in site.data.p %}{% if a.id == "ai_alignment" %}<li><details open>
  <summary>{% include post.html id = a.id %}</summary>
  {% include list.html list = a.children %}
</details></li>{% break %}{% endif %}{% endfor %}</ul>
