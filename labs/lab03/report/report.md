---
## Front matter
title: "Отчет по лабораторной работе №3"
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

**Цель работы:** научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

– Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.

– В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д.)

# Выполнение лабораторной работы

## Подготовка отчета в markdown

1)Изменили название титульного листа

![Меняем название](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/Снимок экрана от 2022-04-28 14-57-07.png){ #fig:001 width=70% }

Оставляем беез изменений все до цели работы(можно убрать список таблиц по желанию)

![Пролистываем до цели работы](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/Снимок экрана от 2022-04-28 14-38-53.png){ #fig:002 width=70% }

Формулируем цель работы

![Формулировка цели работы](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/Снимок экрана от 2022-04-28 14-39-51.png){ #fig:003 width=70% }

Формулируем требуемое задание 

![Формулировка требуемого задания ](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/Снимок экрана от 2022-04-28 14-39-57.png){ #fig:004 width=70% }

Выполнение самой лабораторной работы: копируем текст с отчета и вставляем ссылки на картинки

![Выполнение лабораторной работы](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/Снимок экрана от 2022-04-28 15-29-50.png){ #fig:005 width=70% }

Формулируем вывод.

![Формулировка вывода](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/Снимок экрана от 2022-04-28 14-40-15.png){ #fig:006 width=70% }

## Компиляция 

2)Компиляция в форматы docx и pdf с помощью команды make

![Компиляция](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/Снимок экрана от 2022-04-28 14-40-51.png){ #fig:007 width=70% }

# Вывод

**Вывод:** в ходе выполнения лабораторной работы я научился оформлять отчеты с помощью языка разметки markdown




