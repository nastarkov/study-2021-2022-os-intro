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

# Лабораторная работа №6

## Цель работы

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

## Запись файлов в file.txt

Записываем в файл file.txt названия файлов, содержащихся в каталоге /etc. Дописываем в этот же файл названия файлов, содержащихся в домашнем каталоге

![Запись в file.txt названия файлов из каталога /etc и домашнего каталога](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 15-46-59.png){ #fig:001 width=70% }

Выводим имена всех файлов из file.txt, имеющих расширение .conf, после записываем их в новый текстовый файл conf.txt

![Вывод файлов и их запись в новый текстовый файл](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 15-47-04.png){ #fig:002 width=70% }


## Поиск файлов с помощью команды find

Определяем, какие файлы в домашнем каталоге имеют имена, начинающиеся с символа "с" с помощью команды find

![Поиск файлов, начинающиеся с символа "с"](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-42-20.png){ #fig:003 width=70% }

## Поиск файлов с помощью команды find

Выводим на экран имена файлов, начинающиеся с символа h из каталога /etc
 
![Поиск файлов, начинающиеся с символа "h"](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-41-58.png){ #fig:004 width=70% }

## Поиск файлов с помощью команды find

Запускаем в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена которых начинаются с log

![Запускаем процесс записи в файл файлов, начинающихся с log](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-50-07.png){ #fig:005 width=70% }

## Редактор gedit

Запускаем из консоли в фоновом режиме редактор gedit

![Запуск в фоновом режиме редактора gedit](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-52-10.png){ #fig:007 width=70% }

Определяем идентификатор процесса gedit, используя команду ps, конвейер и фильтр grep

![Определение идентификатора процесса gedit](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-52-15.png){ #fig:008 width=70% }

## Редактор gedit

Читаем справку команды kill c помощью команды man, после чего используем ее для завершения процесса gedit

![Справка команды kill](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-52-30.png){ #fig:009 width=70% }

## Редактор gedit

![Завершение процесса gedit](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-53-51.png){ #fig:010 width=70% }

## Команды df и du

Выполняем команды df и du, предварительно получаем более подробную информацию об этих командах с помощью команды man

![Информация о команде df](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-54-24.png){ #fig:011 width=70% }

## Команды df и du

![Информация о команде du](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-54-47.png){ #fig:012 width=70% }

## Команды df и du

![Команда df в действии](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-55-07.png){ #fig:013 width=70% }

## Команды df и du

![Команда du](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-55-44.png){ #fig:014 width=70% }

## Команды df и du

![Команда du в действии](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-55-35.png){ #fig:015 width=70% }

## Вывод всех директорий с домашнего каталога

Воспользовавшись справкой команды find, выводим имена всех директорий, имеющихся в домашнем каталоге

![Вывод всех директорий, имеющихся в домашнем каталоге](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-56-24.png){ #fig:016 width=70% }

![Вывод всех директорий, имеющихся в домашнем каталоге](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab06/report/image/Снимок экрана от 2022-05-05 14-56-39.png){ #fig:017 width=70% }

## Вывод

В ходе выполнение лабораторной работы я ознакомился с инструментами поиска файлов и фильтрации текстовых данных, приобрел практические навыки: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

