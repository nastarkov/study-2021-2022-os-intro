---
## Front matter
title: "Отчет по второму этапу проекта"
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

**Цель работы:** научиться загружать информацию о себе, аватарку, выкладывать посты

# Выполнение второго этапа проекта

1)Размещаем фотографию владельца сайта

![Сохранение картинки из интернета в нужную папку](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-03-40.png){ #fig:001 width=70% }

![Фото на сайте](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-04-04.png){ #fig:002 width=70% }

2)Размещаем краткое описание владельца сайта (Biography).

![Запись информации о биографии в файле index.md](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-03-09.png){ #fig:003 width=70% }

![Информация о биографии на сайте](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-03-52.png){ #fig:004 width=70% }

3)Добавляем информацию об интересах (Interests).

![Запись информации об интересах в файле index.md](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-02-56.png){ #fig:005 width=70% }

![Информация об интересах на сайте](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-03-56.png){ #fig:006 width=70% }

4)Добавляем информацию от образовании (Education)
 
![Запись информации об образовании в файле index.md](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-03-04.png){ #fig:007 width=70% }

![Информация об образовании на сайте](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-12-07.png){ #fig:008 width=70% }

5)Делаем пост по прошедшей неделе

![Создаем папку с информацией о прошлой неделе](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-04-23.png){ #fig:009 width=70% }

Скачиваем фотографию и в файле index.md пишем информацию, которую будем загружать на сайт

![Файл index.md и обложка поста](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-04-28.png){ #fig:010 width=70% }

![Вид на пост с сайта](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-04-38.png){ #fig:011 width=70% }

![Вид на пост, если перейти по ссылке на него](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-04-56.png){ #fig:012 width=70% }

6)Добавбляем пост на тему управление версиями. Git.

![Создание необходимой папки](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-04-45.png){ #fig:013 width=70% }

![Файл index.md и обложка поста](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-19-12.png){ #fig:014 width=70% }

![Вид на пост с сайта](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-04-50.png){ #fig:015 width=70% }

![Вид на пост, если перейти по ссылке на него](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2022-05-06 19-05-02.png){ #fig:016 width=70% }

# Вывод

**Вывод:** в ходе выполнение второго этапа проекта я научился выкладывать посты, фотографии и добавлять информацию о себе.

