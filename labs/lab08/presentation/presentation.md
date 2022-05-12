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

# Лабораторная работа №8

## Цель работы

**Цель работы:** познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах


## Создание нового файла с использованием vi

1)Создаем каталог с именем ~/work/os/lab06 и переходим в него. Далее вызываем vi и создаем новый файл

![Создание каталога и запуск vi](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-26-47.png){ #fig:001 width=70% }

## Работа в редакторе

2)Нажимаем кнопку i и вводим следующий текст

![Ввод текста](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-41-05.png){ #fig:002 width=70% }

## Работа в редакторе

3)Нажимаем клавишу Esc для перехода в командный режим после завершения ввода текста. Далее нажимаем : для перехода в режим последней строки. После вводим w(записать) и q(выйти), после нажимаем клавишу Enter для сохраненя текста и завершения работы 

![Сохранение и завершение работы](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-42-16.png){ #fig:004 width=70% }

## Работа в редакторе

4)Делаем файл исполняемым 

![Команда chmod +x](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-42-51.png){ #fig:005 width=70% }

## Редактирование существующего файла

1)Вызываем vi на редактирование файла

![Вызов vi](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-43-22.png){ #fig:006 width=70% }

2)Устанавливаем курсор в конец слова HELL с помощью горячих клавиш

![Уставнока курсора](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-44-44.png){ #fig:007 width=70% }

## Редактирование существующего файла

3)Переходим в режим вставки и заменяем HELL на HELLO

![Замена слова](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-45-17.png){ #fig:008 width=70% }

## Редактирование существующего файла

4)Устанавливаем курсор на 4 строку и стираем слово LOCAL

![Удаление слова](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-46-32.png){ #fig:009 width=70% }

## Редактирование существующего файла

5)Переходим в режим вставки и пишем слово local, нажимаем Esc для возврата командный режим

![Добавление слова](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-47-12.png){ #fig:010 width=70% }

## Редактирование существующего файла

6)Устанавливаем курсор на последней строке файла с помощью клавиши G. Вставляем после нее строку : echo $HELLO. Нажимаем Esc ля перехода в командный режим

![Добавление строки](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-49-48.png){ #fig:011 width=70% }

## Редактирование существующего файла

7)Удаляем последнюю строку
 
![Удаление строки](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-50-15.png){ #fig:012 width=70% }

## Редактирование существующего файла

8)Вводим команду отмены изменений (u) для отмены последней команды

![Отмена последнего действия](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-50-36.png){ #fig:013 width=70% }

## Редактирование существующего файла

9)Вводим ":". Сохраняем изменения (w) и выходим из vi (q)

![Сохранение и завершение работы](/afs/.dk.sci.pfu.edu.ru/home/n/a/nastarkov/work/study/2021-2022/Операционные системы/os-intro/labs/lab08/report/image/Снимок экрана от 2022-05-12 13-51-01.png){ #fig:014 width=70% }

## Вывод

**Вывод:** в ходе выполнение лабораторной работы я познакомился с операционной системой Linux. Получил практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах

