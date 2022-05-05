---
## Front matter
lang: ru-RU

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

# Лабораторная работа №5

## Цель работы

Ознакомление с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.

## Копирование файлов и каталогов. Команда cp

Копируем файл /usr/include/sys/io.h в домашний каталог

![Копирование файла в домашний каталог](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-04 16-46-09.png){ #fig:001
 width=70% }

Создаем в домашнем каталоге файл abc1 и копируем его в каталог ~/ski.plases, называем его equiplist2.

![Копирование файла в каталог и изменение названия](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-04 16-48-36.png){ #fig:002 width=70% }

Копируем файл ~/feathers в файл ~/file.old

![Копирование одного файла в другой](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-04 17-00-35.png){ #fig:003 width=70% }

Копируем каталог ~/play в каталог ~/fun

![Копирование одного каталога в другой](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-04 17-44-37.png){ #fig:004 width=70% }

## Перемещение файлов и каталогов. Команда mv

Перемещаем файл equipment в каталог ~/ski.plases

![Перемещение директории в каталог](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-04 16-46-21.png){ #fig:005 width=70% }

Перемещаем файлы ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment

![Перемещение файлов в каталог](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-04 16-51-08.png){ #fig:006 width=70% }

Перемещаем файл ~/file.old в каталог ~/play

![Перемещение файла в каталог](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-04 17-44-31.png){ #fig:007 width=70% }

## Изменение имени файла и каталога. Команда mv

Переименовываем файл ~/ski.plases/equipment в ~/ski.plases/equiplist

![Переименовывание файла](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-04 16-46-28.png){ #fig:008 width=70% }

Перемещаем каталог ~/fun в каталог ~/play и называем его games.

![Переименовывание файла](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-05 13-46-05.png){ #fig:009 width=70% }

## Изменение прав доступа. Команда chmod

Определяем опции команды chmod, необходимые для того, чтобы присвоить перечисленным ниже файлам выделенные права доступа, считая, что в начале таких прав нет.

![Присвоение определенных прав доступа](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-05 12-50-33.png){ #fig:010 width=70% }

Лишаем владельца файла ~/feathers права на чтение. Просматриваем файл командой cat. Видим надпись "Отказано в доступе". При копировании видим надпись "Отказано в доступе"

![Изменение прав доступа. Проверка](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-05 13-02-52.png){ #fig:011 width=70% }

## Команда man

По команде man читаем описание команд mount, mkfs, fsck, kill

![Описание команды mount](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-05 13-12-58.png){ #fig:012 width=70% }

## Команда man

![Описание команды fsck](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-05 13-13-56.png){ #fig:013 width=70% }

## Команда man

![Описание команды kill](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-05 13-12-06.png){ #fig:014 width=70% }

## Команда man

![Описание команды mkfs](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab05/report/image/Снимок экрана от 2022-05-05 13-13-40.png){ #fig:015 width=70% }
