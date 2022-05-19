---
## Front matter
lang: ru-RU
title: Презентация к лабораторной работе №9
author: |
         Старков Никита Алексеевич
	
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
	
## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

## Цель работы

**Цель работы:** познакомиться с операционной системой Linux.Получить практические навыки работы с редактором Emacs.

## Основные команды Emacs

1)Открыл emacs:

![Emacs.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 16-56-11.png){ #fig:001 width=70% }

## Основные команды Emacs

2)Создал файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f (C-x C-f):

![Создание файла lab07.sh.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 16-58-49.png){ #fig:002 width=70% }

## Основные команды Emacs

3)Набрал текст:

![Ввод текста.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-01-23.png){ #fig:003 width=70% }

## Основные команды Emacs

4)Сохранил файл с помощью комбинации Ctrl-x Ctrl-s (C-x C-s):

![Сохранение.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-02-21.png){ #fig:004 width=70% }

## Стандартные процедуры

5) Проделал с текстом стандартные процедуры редактирования, каждое действие должно осуществляться комбинацией клавиш:

5.1. Вырезать одной командой целую строку (С-k):

![Вырезание строки. ](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-02-56.png){ #fig:005 width=70% }

## Стандартные процедуры

5.2  Вставить эту строку в конец файла (C-y).:

![Вставка в конец файла.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-03-05.png){ #fig:006 width=70% }

## Стандартные процедуры

5.3 Выделить область текста (C-space):

![Выделение.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-07-55.png){ #fig:007 width=70% }

## Стандартные процедуры

5.4 Скопировать область в буфер обмена (M-w). А затем вставить область в конец файла.

![Вставка.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-07-06.png){ #fig:008 width=70% }

## Стандартные процедуры

5.5 Вновь выделить эту область и на этот раз вырезать её (C-w):

![Вырезание.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-07-44.png){ #fig:009 width=70% }

## Стандартные процедуры

5.6 Отмена последнего действия (C-/)у:
 
![Отмена последнего действия.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-08-07.png){ #fig:010 width=70% }

## Стандартные процедуры

6)Научился использовать команды по перемещению курсора:

6.1 Перемещение курсора в начало строки (C-a):

![Перемещение курсора в начало строки.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-09-46.png){ #fig:011 width=70% }

## Стандартные процедуры

6.2 Перемещение курсора в конец строки (C-e):

![Перемещение курсора в конец строки.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-09-59.png){ #fig:0012 width=70% }

## Стандартные процедуры

6.3 Перемещение курсора в начало буфера обмена (M-<):

![Перемещение курсора в начало буфера обмена.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-12-14.png){ #fig:013 width=70% }

## Стандартные процедуры

6.4 Перемещение курсора в конец буфера обмена (M->):

![Перемещение курсора в конец буфера обмена.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-23-57.png){ #fig:014 width=70% }

## Стандартные процедуры

7) Управлять буферами:

7.1 Вывести список активных буферов на экран (C-x C-b):

![Выведение списка.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-28-55.png){ #fig:015 width=70% }

## Стандартные процедуры

7.2 Переместиться во вновь открытое окно (C-x) o со списком открытых буферов и переключиться на другой буфер:

![Переключение на другой буфер.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-29-47.png){ #fig:016 width=70% }

## Стандартные процедуры

7.3 Закрыть окно (C-x 0) и вновь переключиться между буферами, но уже без вывода их списка на экран (C-x b):
 
![Переключение без вывода списка на экран.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-24-36.png){ #fig:017 width=70% }

## Стандартные процедуры

8) Освоил управление окнами:

8.1. Поделить фрейм на 4 части: разделить фрейм на два окна по вертикали (C-x 3), а затем каждое из этих окон на две части по горизонтали (C-x 2).

![Деление на 4 части.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-36-02.png){ #fig:018 width=70% }

## Стандартные процедуры

8.2 В каждом из четырёх созданных окон открыть новый буфер (файл) и ввести несколько строк текста:

![Создание файлов.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-36-59.png){ #fig:019 width=70% }

## Стандартные процедуры

![Вставка нескольких строк текста.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-42-21.png){ #fig:020 width=70% }

## Стандартные процедуры

9)Режим поиска:

9.1. Переключил в режим поиска (C-s) и нашел несколько слов, присутствующих в тексте:

![Поиск слов.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-43-23.png){ #fig:021 width=70% }

## Стандартные процедуры

9.2 Попробовал использовать другой режим поиска, нажав M-s o:

![Другой режим поиска.](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab09/report/image/Снимок экрана от 2022-05-18 17-44-24.png){ #fig:022 width=70% }

## Вывод

**Вывод:** в ходе выполнения лабораторной работы я познакомился с операционной системой Linux: получил практические навыки работы с редактором Emacs.

