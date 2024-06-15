---
layout: post
title: Агент, оптимизирующий ожидаемую полезность
translated_by: К. Кирдан
translation_details: "с небольшими сокращениями, добавлены ссылки"
excerpt: "У агента, оптимизирующего ожидаемую полезность, есть какой-то способ непротиворечиво оценивать все возможные последствия его действий, и он взвешивает свои действия по ожидаемой полезности их последствий."
math: true
original: https://arbital.com/p/expected_utility_agent/
license: https://creativecommons.org/licenses/by/3.0/deed.ru
---
У агента, оптимизирующего [ожидаемую полезность][expected_utility], есть какой-то способ непротиворечиво оценивать все возможные последствия его действий, и он взвешивает свои действия по ожидаемой полезности их последствий. Например, если действие с 50%-ной вероятностью приведет к итогу с полезностью 20, с 25%-ной вероятностью приведет к итогу с полезностью 35 и с 25%-ной вероятностью приведет к итогу с полезностью 45, то оно будет иметь ожидаемую полезность $0.5 \cdot 20 + 0.25 \cdot 35 + 0.25 \cdot 45 = 30$. Эти полезности в принципе могут отражать [любой вид][orthogonality] морали или ценностей — эгоизм, альтруизм или [скрепки][paperclip]. Несколько [известных математических теорем][coherence_theorems] предполагают, что если вас нельзя рассматривать как агента, оптимизирующего ожидаемую полезность, то вы, должно быть, ходите кругами, делаете плохие ставки или демонстрируете другое вредное поведение. Ряд известных экспериментов показывают, что люди действительно демонстрируют такое поведение, и их нельзя рассматривать как агентов, оптимизирующих ожидаемую полезность.

{% include routes.html %}