---
layout: page
permalink: /explore/ai_alignment
title: Согласование ИИ
---
<h2 style="margin-top:0; text-align:center">Согласование ИИ</h2>

### Переведенные материалы (в контексте исходной иерархии):

<!-- ПРИМЕР ДРЕВОВИДНОГО СПИСКА
<ul class="tree"><li>
  <details open><summary>Планеты гиганты</summary><ul>
    <li><details open><summary>Газовые</summary><ul>
      <li>Юпитер<br>Коммент</li>
      <li>Сатурн</li>
    </ul></details></li>
    <li><details open><summary>Ледяные</summary><ul>
      <li>Уран</li>
      <li>Нептун</li>
    </ul></details></li>
  </ul></details>
</li></ul> -->

<ul class="tree" style="margin-left: -1.5rem"><li><details open><summary>{% include post.html id = "ai_alignment" %}</summary><ul>
  <li><details open><summary>{% include post.html id = "advanced_safety" %}</summary><ul>
    <li><details open><summary>{% include post.html id = "unbounded_analysis" %}</summary><ul>
      <li><details open><summary>{% include post.html id = "AIXI" %}</summary><ul>
        <li>(еще 1 пункт)</li>
      </ul></details></li>
      <li>{% include post.html id = "solomonoff_induction" %}</li>
      <li>(еще 5 пунктов и 1 подпункт)</li>
    </ul></details></li>
    <li>(еще 10 пунктов и 6 подпунктов)</li>
  </ul></details></li>
  <li><details open><summary>{% include post.html id = "advanced_agent_theory" %}</summary><ul>
    <li><details open><summary>{% include post.html id = "advanced_agent" %}</summary><ul>
      <li><details open><summary>{% include post.html id = "Vingean_uncertainty" %}</summary><ul>
        <li>{% include post.html id = "Vinge_law" %}</li>
        <li>(еще 1 пункт)</li>
      </ul></details></li>
      <li>(еще 14 пунктов и 5 подпунктов)</li>
    </ul></details></li>
    <li><details open><summary>{% include post.html id = "instrumental_convergence" %}</summary><ul>
      <li><details open><summary>{% include post.html id = "convergent_strategies" %}</summary><ul>
        <li>{% include post.html id = "preference_stability" %}</li>
        <li>(еще 1 пункт)</li>
      </ul></details></li>
      <li><details open><summary>{% include post.html id = "paperclip_maximizer" %}</summary><ul>
        <li>(еще 2 пункта)</li>
      </ul></details></li>
      <li>(еще 3 пункта)</li>
    </ul></details></li>
    <li><details open><summary>{% include post.html id = "orthogonality" %}</summary><ul>
      <li><details open><summary>{% include post.html id = "paperclip_maximizer" %}</summary><ul>
        <li>(еще 2 пункта)</li>
      </ul></details></li>
      <li>(еще 2 пункта)</li>
    </ul></details></li>
  </ul></details></li>
  <li><details open><summary>{% include post.html id = "value_alignment_value" %}</summary><ul>
    <li>{% include post.html id = "frankena_goods" %}</li>
    <li>(еще 6 пунктов и 1 подпункт)</li>
  </ul></details></li>
  <li><details open><summary>{% include post.html id = "Vingean_reflection" %}</summary><ul>
    <li><details open><summary>{% include post.html id = "reflective_stability" %}</summary><ul>
      <li>{% include post.html id = "preference_stability" %}</li>
      <li>(еще 2 пункта и 2 подпункта)</li>
    </ul></details></li>
    <li>{% include post.html id = "Vinge_principle" %}</li>
    <li>(еще 2 пункта)</li>
  </ul></details></li>
  <li>{% include post.html id = "some_computations_are_people" %}</li>
  <li>(еще 39 пунктов и около 100 подпунктов)</li>
</ul></details></li></ul>

---

### Все материалы:

...раздел в разработке...

<!--
{% for t in site.data.p %}{% if t.id == "ai_alignment" %}
{% include post.html id = t.id %}
{% for c1 in t.children %}
- {% include post.html id = c1 %}
  {% for t1 in site.data.p %}{% if t1.id == c1 and t1.children %}{% for c2 in t1.children %}
    - {% include post.html id = c2 %}
  {% endfor %}{% endif %}{% endfor %}
{% endfor %}
{% endif %}{% endfor %}
-->
