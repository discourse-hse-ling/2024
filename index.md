> Туман рассеивается, если изучать явления языка в примитивных формах его употребления, где четко прослеживается назначение слов и то, как они функционируют.

# формула оценки
0.2 × мини-тесты + 0.2 × квизы + 0.3 × домашки + 0.3 × экзамен

---

# пары

{% for lecture in site.data.lectures %}
## лекция {{ lecture.n }} --- {{ lecture.title }}
[слайды]({{ lecture.slides }})
{% endfor %}
---

# домашние задания

{% for assignment in site.data.assignments %}
## [{{ assignment.title }}]({{ assignment.link }})
<!--[ссылка]({{ assignment.link }}) -->

группа 1 | группа 2
{{ assignment.dl-1 }} | {{assignment.dl-2}}
{% endfor %}
