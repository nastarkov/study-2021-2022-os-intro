---
## Front matter
title: "Отчет по шестому этапу проекта"
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

**Цель работы:** научиться переводить сайт на английский язык, выложить пост по прошедшей неделе и пост на любую тему

# Выполнение шестого этапа проекта

1)Скачиваем с сайта wowchemy файлы en.yaml и ru.yaml, предварительно создаем каталог i18n.

![Файл en.yaml](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 12-55-35.png){ #fig:001 width=70% }

![Файл ru.yaml](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 13-06-32.png){ #fig:002 width=70% }

2)Создаем папки en и ru, куда копируем все содержимое каталога /work.blog/content 

![Папки en и ru](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 13-16-41.png){ #fig:003 width=70% }

3)В папке ru меняем все содержимое на русский язык, в папке en на английский язык.

4)В каталоге _default меняем содержимое файла language. 

![languages.yaml](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 13-21-00.png){ #fig:004 width=70% }

В этом же каталоге создаем файлы menus.en.yaml и menus.ru.yaml. В menus.ru.yaml меняем текст на русский

![menus.en.yaml и menus.ru.yaml](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 13-25-51.png){ #fig:005 width=70% }

Получаем готовый сайт с переводом на английский и русский языки:

![Сайт на русском языке](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 14-45-37.png){ #fig:006 width=70% }

![Сайт на русском языке](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 14-45-45.png){ #fig:007 width=70% }

![Сайт на русском языке](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 14-45-49.png){ #fig:008 width=70% }

![Сайт на русском языке](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 14-45-54.png){ #fig:009 width=70% }

![Сайт на русском языке](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 14-45-58.png){ #fig:010 width=70% }

![Сайт на русском языке](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 14-46-44.png){ #fig:011 width=70% }

![Сайт на английском языке](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 14-46-44.png){ #fig:012 width=70% }

![Сайт на английском языке](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 14-46-44.png){ #fig:013 width=70% }

![Сайт на английском языке](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 14-46-44.png){ #fig:014 width=70% }

![Сайт на английском языке](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 14-46-44.png){ #fig:015 width=70% }

![Сайт на английском языке](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 14-46-44.png){ #fig:016 width=70% }

![Сайт на английском языке](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 14-46-44.png){ #fig:017 width=70% }

5)Добавляем пост по прошедшей неделе 

![Пост на сайте](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 15-16-31.png){ #fig:018 width=70% }

![Пост на сайте](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 15-17-41.png){ #fig:019 width=70% }

3)Добавляем пост на тему "Смысл бытия"

![Пост на сайте](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 15-16-24.png){ #fig:020 width=70% }

![Пост на сайте](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2022-06-02 15-17-55.png){ #fig:021 width=70% }

# Вывод

**Вывод:** в ходе выполнения шестого этапа проекта я перевел сайт на английский язык, выложил пост по прошедшей неделе и пост на любую тему

