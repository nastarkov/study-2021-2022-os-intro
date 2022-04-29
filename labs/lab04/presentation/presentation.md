---
## Front matter
lang: ru-RU

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

# Лабораторная работа №4

## Определение полного имени домашнего каталога

Это мы сможем реализовать посредством команды pwd

![Полное имя домашнего каталога](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab04/report/image/Снимок экрана от 2022-04-28 16-15-20.png){ #fig:001 width=70% }

## Вывод содержимого с помощью команды ls

В каталоге tmp создаем файлы и показываем их наличие с помощью команды ls

![Каталог /tmp](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab04/report/image/Снимок экрана от 2022-04-28 16-15-41.png){ #fig:002 width=70% }

Аналогично проверяем в наличие подкаталога cron

![Подкаталог cron](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab04/report/image/Снимок экрана от 2022-04-28 16-18-51.png){ #fig:003 width=70% }

## Работа в домашнем каталоге. Команда mkdir и rm -r

Переходим в домашний каталог и создаем каталог newdir. В каталоге ~/newdir создаем новый каталог с именем morefun. В домашнем каталоге создаем одной командой три новых каталога с именами letters,memos,misk. Затем удаляем эти каталоги одной командой 

![Создание и удаление каталогов](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab04/report/image/Снимок экрана от 2022-04-28 16-22-47.png){ #fig:005 width=70% }

## Команда man

Используем команду man ls. Определяем, какую опцию команды ls нужно использовать для просмотра содержимого не только указанного каталога, но и подкаталогов, входящих в него. С помощью команды man определяем набор опций команды ls, позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталог развёрнутым описанием файлов.

![Команда man ls](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab04/report/image/Снимок экрана от 2022-04-28 16-29-50.png){ #fig:007 width=70% }

![Команда man ls](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab04/report/image/Снимок экрана от 2022-04-28 16-30-01.png){ #fig:008 width=70% }

Таким же образом, используем команды man cd, man pwd, man mkdir, man rmdir, man rm

![Другие комбинации с man](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab04/report/image/Снимок экрана от 2022-04-29 15-40-00.png){ #fig:009 width=70% }

## Команда history

Далее используем команду history

![Команда history](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab04/report/image/Снимок экрана от 2022-04-29 15-41-15.png){ #fig:0010 width=70% }

## Команда history

Выполняем модификацию и исполнение нескольких команд из буфера обмена

![Модификация команды](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab04/report/image/Снимок экрана от 2022-04-29 15-45-21.png){ #fig:0011 width=70% }


