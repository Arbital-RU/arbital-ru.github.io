---
layout: page
permalink: "/"
title: Главная
excerpt: "Здесь выкладываются переводы статей с сайта arbital.com, посвященного согласованию искусственного интеллекта и математике."
---
Здесь выкладываются переводы статей с сайта [arbital.com](https://arbital.com), посвященного согласованию искусственного интеллекта и математике.

Больше материалов на близкие темы можно найти на сайте русскоязычного сообщества [LessWrong](https://lesswrong.ru/), а также на сайте о [безопасности ИИ](https://aisafety.ru/).

<hr style="margin: 4px 0 0 0">

<h3><b>Разделы:</b></h3>

{% include domains.html info = true %}

<hr style="margin: 12px 0 0 0">

<h3><b>Последние переводы:</b></h3>

{% for p in site.posts limit: 6 %}
<div class="post" style="margin:16px">
<div class="post-date" style="margin:0">{{ p.date | date: "%Y.%m.%d" }}</div>
<a href="{{ p.url }}">{{ p.title }}</a>
</div>
{% endfor %}

<hr class="hrdark" style="margin-bottom: 16px">

<small>
Все материалы распространяются по лицензии <a href="https://creativecommons.org/licenses/by/3.0/deed.ru">CC BY 3.0</a>, если не отмечено иное. Предложить свои переводы или правки можно <a href="https://github.com/Arbital-RU/arbital-ru.github.io">через GitHub</a>, либо связавшись с администраторами:
</small>
<ul style="margin-top: 12px">
  <li><small>К. Кирдан — <a href="https://vk.com/latif_rosh">ВКонтакте</a>, <a href="https://t.me/KKirdan">Telegram</a>, эл. почта <a href="mailto:latif.rosh@gmail.com">latif.rosh@gmail.com</a></small></li>
</ul>
