---
layout: page
permalink: /explore/math
title: Математика
excerpt: "Математика"
---
{% include domains.html domain = "math" %}

**Переведено:**
<ul>
{% for a in site.data.p %}
{% if a.domains contains "math" and a.translated %}
  <li>{% include post.html id = a.id %}</li>
{% endif %}
{% endfor %}
</ul>

**Не переведено:**
<ul>
{% for a in site.data.p %}
{% if a.domains contains "math" %}{% unless a.translated or a.deleted %}
  <li>{% include post.html id = a.id %}</li>
{% endunless %}{% endif %}
{% endfor %}
</ul>

<!--
**Не будет переводиться:**
<ul>
{% for a in site.data.p %}
{% if a.domains contains "math" and a.deleted %}
  <li>{% include post.html id = a.id %}</li>
{% endif %}
{% endfor %}
</ul>
-->
