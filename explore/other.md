---
### Этой страницы не было на оригинальном сайте
layout: page
permalink: /explore/other
title: Прочее
excerpt: ""
---
**Переведено:**
<ul>
{% for a in site.data.p %}
{% unless a.domains contains "AI" %}{% unless a.domains contains "math" %}{% if a.translated %}
  <li>{% include post.html id = a.id %}</li>
{% endif %}{% endunless %}{% endunless %}
{% endfor %}
</ul>

**Не переведено:**
<ul>
{% for a in site.data.p %}
{% unless a.domains contains "AI" %}{% unless a.domains contains "math" %}{% unless a.translated %}
  <li>{% include post.html id = a.id %}</li>
{% endunless %}{% endunless %}{% endunless %}
{% endfor %}
</ul>

...данные дополняются...
