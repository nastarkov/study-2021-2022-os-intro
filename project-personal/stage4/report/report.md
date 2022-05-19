---
## Front matter
title: "Отчет по четвертому этапу проекта"
subtitle: "*дисциплина: Операционные системы *"
author: "Старков Никита Алексеевич"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

**Цель работы:** научиться добавлять ссылки на сайт, выложить пост по прошедшей неделе и пост на тему "Оформление отчета"

# Выполнение четвертого этапа проекта

1)Заходим в /work/blog/content/authors/admin. Открываем index.md. Меняем ссылки на иконки, добавляем новые ссылки, копируем сами иконки с сайта, который указанам в файле index.md

![Добавление ссылок](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage4/report/image/Снимок экрана от 2022-05-19 15-20-17.png){ #fig:001 width=70% }

![Вид на ссылки с сайта](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage4/report/image/Снимок экрана от 2022-05-19 15-20-32.png){ #fig:002 width=70% }

2)Добавляем пост по прошедшей неделе
 
![Информация о посте в файле](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage4/report/image/Снимок экрана от 2022-05-19 15-18-33.png){ #fig:003 width=70% }

![Пост на сайте](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage4/report/image/Снимок экрана от 2022-05-19 15-18-47.png){ #fig:004 width=70% }

![Пост на сайте](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage4/report/image/Снимок экрана от 2022-05-19 15-18-57.png){ #fig:005 width=70% }

3)Добавляем пост на тему "Оформлении отчета"

![Информация о посте в файле](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage4/report/image/Снимок экрана от 2022-05-19 15-19-43.png){ #fig:006 width=70% }

![Пост на сайте](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage4/report/image/Снимок экрана от 2022-05-19 15-19-55.png){ #fig:007 width=70% }

![Пост на сайте](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage4/report/image/Снимок экрана от 2022-05-19 15-20-03.png){ #fig:008 width=70% }

# Вывод

**Вывод:** в ходе выполнения третьего этапа проекта я научился добавлять ссылки на сайт, выложил пост по прошедшей неделе и пост на тему "Оформление отчета"

