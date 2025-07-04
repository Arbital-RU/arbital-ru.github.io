---
layout: post
title: Рефлексивная устойчивость
translated_by: К. Кирдан
translation_details: "добавлены ссылки"
excerpt: "Агент «рефлексивно устойчив» в некотором отношении, если сделав выбор создать агента-преемника или изменить свой собственный код, он создает только такого преемника, который в этом отношении думает также, как и создатель."
original: https://arbital.com/p/reflective_stability
license: https://creativecommons.org/licenses/by/3.0/deed.ru
---
[Агент][advanced_agent] «рефлексивно устойчив» в некотором отношении, если сделав выбор создать агента-преемника или изменить свой собственный код, он создает _только_ такого преемника, который в этом отношении думает также, как и создатель.

* В теории [тайлинговых агентов][tiling_agents] [сатисфаизатор](https://en.wikipedia.org/wiki/Satisficing) [ожидаемой полезности][expected_utility] рефлексивно _[последователен][reflective_consistency]_, поскольку он одобрил бы создание другого сатисфаизатора ожидаемой полезности, но он не является рефлексивно _устойчивым_, поскольку он мог бы одобрить также и создание максимизатора ожидаемой полезности (т. к. ожидает, что последствия создания максимизатора удовлетворительны).
* [Функция полезности][utility_function], которая [взвешивает только скрепки][paperclip_maximizer] — «рефлексивно устойчива», поскольку максимизаторы скрепок пытаются строить _только_ других максимизаторов скрепок.

Если вы сейчас думаете что-то (в каком-то отношении) и кажется неприемлемым не думать так (в этом отношении), то вы рефлексивно устойчивы (в этом отношении).

{% include routes.html %}
