---
### Этой страницы не было на оригинальном сайте
layout: page
permalink: /explore/other
title: Прочее
excerpt: "Прочее"
---
{% include domains.html domain = "other" %}

**Переведено:**
<ul>
{% for a in site.data.p %}
{% unless a.domains contains "ai_alignment" or a.domains contains "math" %}{% if a.translated %}
  <li>{% include post.html id = a.id %}</li>
{% endif %}{% endunless %}
{% endfor %}
</ul>

**Не переведено:**
<ul>
{% for a in site.data.p %}
{% unless a.domains contains "ai_alignment" or a.domains contains "math" %}{% unless a.translated or a.deleted %}
  <li>{% include post.html id = a.id %}</li>
{% endunless %}{% endunless %}
{% endfor %}
</ul>

...данные дополняются...
