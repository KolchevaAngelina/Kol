# NP Сетевые системы и приложения - ВТОРОЙ СЕМЕСТР

# Страничка семинаров ПИ22-1 ПИ22-2 ПИ22-3 ПИ22-4




Основные темы практики:
---

Первый семестр:

* ~~[ОСНОВЫ LINUX](https://github.com/VladimirAndropov/fa-os-practice/README.md)~~



Второй семестр:

 * [Сетевые приложения](#брс) 




Материалы курса
---
Вы можете познакомиться с материалами курса - презентациями к лекциям, методических рекомендациям к лабораторным работам на [github](http://koroteev.site/os/).

 Плейлист с видео по данному курсу досупен на [YouTube](https://www.youtube.com/playlist?list=PLhgyvraU60gU8OAhjtcipU_sO7UYvkQl9). 


# План семинарных занятий


- Системы контроля версий
  - Вначале мы изучаем git для совместной разработки
  - Учимся настраивать синхронизацию проектов через GitHub
 
- Использование сокетов
  - Затем создаем простейшее серверное приложение, которое отправляет потоковое видео

- Веб-сервер
  - Развиваем предыдущий опыт в сокетах до создания простейшего http веб-сервера 
  - Добавляем функционал многопоточности для http веб-сервера 
  - Добавляем функционал многопроцессности для ускорения http веб-сервера 
  - Добавляем библиотеки асинхронного программирования для http веб-сервера


Вторая половина семестра
- Развертывание сетевых приложений
  - Пакуем в контейнер - развертываем http асинхронный параллельный веб-сервер на удаленном ресурсе (hub.docker.com)


# БРС

## Первая половина семестра

| Cеминар/Лекция дата  |  № п/п  | Вид учебной деятельности| Максимум  за семестр |
| :---         |     :---:      |      :---:      |          ---: |
|  [Лекция DO1.0](https://youtu.be/HZxQbtYhBYs?si=g7YtSI9QijMIMDlW)   |[ Лабораторная работа-0.1 ](0_git_basics/README.md)  | Работа с Git     | 3    |
| [Лекция DO1.3](https://youtu.be/CE2Ek2dNQLE?si=zRX58WLV3zv-o2Nn)  | [Лабораторная работа-0.2](https://github.com/fa-python-network/0_git_basics)   | сделать форк этого репозитория и открыть его в IDE| -    |
| [Лекция DO1.1](https://youtu.be/TZJKKLTi8b4?si=C3X4B7ikW8B7QjbE)   | Лабораторная работа-0.3   | запушить изменения в проект 1_echo на github     | -    |
|  Домашнее задание DO1.4   | [ Лабораторная работа-0.4](7_TCP_server)   | настроить .gitignore, удалить лишнее| 2    |
| Семинар DO1.0 от 05.02-11.02  | [ Лабораторная работа-0.5 ](7_TCP_server/README.md)  | субмодуль git submodule     | -    |
|  [Лекция NP1.1](https://youtu.be/UTalhmE_WcI?si=jqIVOyhYmaLaeufX)   |[ Лабораторная работа-1.1](https://github.com/fa-python-network/1_echo_server)   | echo-server     | 3    |
|  [Семинар NP1.1 от 12.02-18.02](https://www.youtube.com/watch?v=ZGk4Kvt7vgg)   |[ Лабораторная работа-1.2 ](1_echo_server/задание2/README.md)   |  echo-client  + telnet/putty   | -    |
| Домашнее задание NP1.1  | [ Лабораторная работа-1.3](1_echo_server/README.md)   |  live stream video server    | -    |
|  Семинар NP1.2    |[Лабораторная работа-5.1](5_FTP_server/README.md)  | ftp-сервер (файлы output+file1)     | -    |
|  Домашнее задание NP1.2   |[ Лабораторная работа-5.2](https://github.com/fa-python-network/5_FTP_server)  | файловый менеджер    | 2    |
| Семинар NP4.4 от 19.02-25.02  | [  Лабораторная работа-4.1](4_requests)  | Postman  (запросы к ruz.fa.ru и к echo-server)   | -    |
| [Лекция NP4.4](https://youtu.be/mtq-NRC5Wmk?si=5Mq4c4FXd9ridGSg)  | [ Лабораторная работа-4.2](4_requests)   | код http-клиента из Postman   | 2    |
| [Лекция NP4.5](https://youtu.be/AWi9_OEOojI?si=PtUD0SV0z0e61_ct) | [ Лабораторная работа-6.1](https://github.com/fa-python-network/6_Web_server)   | Низкоуровневая работа с веб  | 3    |
| [Семинар NP4.5 от 26.02-3.03](https://www.youtube.com/watch?v=WCfEuxd6_P4) [(2дубль)](https://www.youtube.com/watch?v=YTULq4oU3GU)  | [  Лабораторная работа-6.2](6_Web_server/README1.md)  | Веб-сервер HTTP Часть1 (webserver1)  | -    |
| Домашнее задание NP4.5  | [ Лабораторная работа-6.3](6_Web_server/README2.md)   | Веб-сервер HTTP  Часть2 (фреймворк+вебсервер)  | -    |
| [Лекция NP2.1](https://youtu.be/_FYcL3tYKec?si=k3cdS1k2qlsWds6E)  | [ Лабораторная работа-2.2 ](https://github.com/fa-python-network/2_threaded_server)  | threaded server    | 3    |
| [Семинар NP2.2](https://www.youtube.com/watch?v=kwB47aGl5IY) | [  Лабораторная работа-3.2](6_Web_server/README3.md)   |  Веб-сервер HTTP  Часть3 (threaded)    | -    |
| Домашнее задание NP2.1  | [ Лабораторная работа-2.1 ](2_threaded_server/README.md)  | threaded+async web-server    | -    |
|  [Лекция NP2.2](https://youtu.be/x4MPG22JTtI?si=Nf0eyJpVU-0sitqW)    |[Лабораторная работа-3.1](https://github.com/fa-python-network/3_Parallelism)  | multiprocessing   | 2    |
| [Семинар NP2.1 от 11.03-17.03](https://www.youtube.com/watch?v=g8T14fWkvOw)  | [  Лабораторная работа-7.1](https://github.com/VladimirAndropov/7_TCP_server)  | UDP/TCP-multiprocess-сервер      | -    |

 ## Вторая половина семестра
| Cеминар/Лекция дата  |  № п/п  | Вид учебной деятельности| Максимум  за семестр |
| :---         |     :---:      |      :---:      |          ---: |
|  [Лекция DO2.1](https://youtu.be/b9tXQsZPJOE?si=dor0L5v5Sr1lUxiz)   |Лабораторная работа-0.7  | настройка pip   | 1    |
| [Лекция DO2.2](https://youtu.be/oKqTB2nJ-Yc?si=T9ACb0-e-6RM-ao9)| Лабораторная работа-0.6  | настройка env   | 1    |
| [Лекция NP4.1](https://youtu.be/wdMx35irNKE?si=0jtSv3UgTjmweXLF)   | [Лабораторная работа-10.1 ](10_apache_nginx/README.md)   | apache  |1    |
| [Лекция NP4.1](https://youtu.be/UpS5s4z6odo?si=a4xe8yusvBcZpzGm)  | [Лабораторная работа-10.2 ](10_apache_nginx/README.md)   | nginx  |1    |
|  Семинар 8.1   |[Лабораторная работа-8.1](8_Assymmetric_ciphers_2022/README.md)  |  Lets_encrypt  | -    |
| Лекция  | [Лабораторная работа-8.2 ](https://github.com/fa-python-network/7_Symmetric_ciphers)   | Основные алгоритмы синхронного шифрования  | 3    |
| Домашнее задание 8.1  | [Лабораторная работа-8.3 ](https://github.com/fa-python-network/8_Assymmetric_ciphers)   | Алгоритмы асимметричного шифрования  | -    |
| Домашнее задание NP2.2   | [Лабораторная работа-3.2 ](https://github.com/fa-python-network/4_asyncio_server) | Асинхронный сервер  | -    |
|   [Лекция DO2.3](https://youtu.be/vd609d2Wc5E?si=-ejWPgaR3afhioZd)   |[Лабораторная работа-13.1 ](https://github.com/fa-python-network/9_flask_app)   |  Создание микросервиса  |5    |
| Семинар DO2.3    | [Лабораторная работа-13.2 ](13_flask_app_2022/README.md)   |  1_echo_server в docker |-    |
| Семинар DO2.3   | [Лабораторная работа-13.3 ](13_flask_app_2022/README.md)   |  5_FTP_server в docker |-    |
| Семинар DO2.3   | [Лабораторная работа-13.4 ](13_flask_app_2022/README.md)   |  6_Web_server в docker |-    |
|  Семинар DO2.4     |[Лабораторная работа-13.5 ](11_Celery_Rabbit/README.md)   | Celery_Rabbit  | -    |
|  [Лекция NP4.3](https://youtu.be/ZyGfUllQ34I?si=5ZcWVlZNN-1_qucG)   |Лабораторная работа-11.1    | балансировка в docker  | 2    |
|  Семинар DO2.5    |[Лабораторная работа-11.2 ](11_Celery_Rabbit/README.md)   | Celery Workers + Queue  |-    |
| -   | -  | Тестовые опросы  | 5    | 


## Пояснение:
- Доля измеримых видов контроля самостоятельной
работы обучающихся, исключающих субъективное суждение = 30 баллов
- Доля cамостоятельной работы обучающегося = 10 баллов 

Выполнение за половину семестра от 7 до 20 баллов, считается
аттестованным

# Примерные задания для подготовки к экзамену
1. Напишите программу, которая создает нить. Родительская и вновь созданная нити должны распечатать десять строк текста. [README](exam/1.md)
2. Напишите простой эхо-сервер, использующий неблокирующие сокеты и клиент к нему.[README](18sem-fs/socket_example.c)
3. Напишите простой многопоточный загрузчик URL. Список URL скрипт принимает как аргументы командной строки.[README](2017/20-socket/README.md)
4. Реализуйте простой HTTP-клиент. Он принимает один параметр командной строки - URL. Клиент делает запрос по указанному URL и выдает тело ответа на терминал как текст.
5. Напишите программу, которая вычисляет число Пи при помощи ряда Эйлера. Количество потоков программы должно определяться параметром командной строки. 
6. Дана функция calculate(x, y). Напишите программу, которая создает пул из 5 процессов и распределяет в этом пуле вычисление функции на промежутке х от 0 до 1 с шагом 0,1. у равняется 2 всегда.[README](2017/24-stdthread/README.md)
7. Напишите программу, которая проверяет все числа от 0 на простоту и выводит простые числа на экран по мере нахождения. Числа должны проверяться в различных потоках (или процессах, по выбору студента) Программа должна работать до тех пор, пока ее не остановит пользователь.
8. Напишите программу, которая обходит все файлы в директории, переданной ей как параметр и выводит на экран имена тех, чей размер задан как второй параметр. Реализовать рекурсивный обход поддиректорий.[README](12sem-fs/README.md)
9. Напишите программу, которая выводит на экран список номеров открытых портов на данной машине. Использовать команду netstat.
10. Напишите программу, которая копирует файл с удаленного хоста в текущую папку по SSH. Имя файла и адрес хоста принимать как параметры.


# Пример экзаменационного билета
Экзаменационный билет №

1. Понятие потокобезопасности. Причины, проблематика, способы обеспечения. (20 баллов)
2. Доступ к общим ресурсам в многопоточной программе. Механизмы блокировки ресурсов модуля threading. (20 баллов)
3. Напишите программу, которая создает четыре нити, исполняющие одну и ту же функцию. Эта функция должна распечатать последовательность текстовых строк, переданных как параметр. Каждая из созданных нитей должна распечатать различные последовательности строк. (20 баллов)

@import url(https://themes.googleusercontent.com/fonts/css?kit=N4duVc9C58uwPiY8\_59Fz0B8CmLstfspW4fBy9KOpPk);ol.lst-kix\_gzze5qyu37i0-4{list-style-type:none}ol.lst-kix\_gzze5qyu37i0-5{list-style-type:none}ol.lst-kix\_gzze5qyu37i0-2{list-style-type:none}ol.lst-kix\_gzze5qyu37i0-1.start{counter-reset:lst-ctn-kix\_gzze5qyu37i0-1 0}ol.lst-kix\_gzze5qyu37i0-3{list-style-type:none}ol.lst-kix\_gzze5qyu37i0-0{list-style-type:none}ol.lst-kix\_gzze5qyu37i0-1{list-style-type:none}ol.lst-kix\_8xt5grgbz7zp-7.start{counter-reset:lst-ctn-kix\_8xt5grgbz7zp-7 0}.lst-kix\_ixj2d4xkj6ca-5>li{counter-increment:lst-ctn-kix\_ixj2d4xkj6ca-5}ol.lst-kix\_o04u6rx3d2ow-4.start{counter-reset:lst-ctn-kix\_o04u6rx3d2ow-4 0}ol.lst-kix\_ixj2d4xkj6ca-7.start{counter-reset:lst-ctn-kix\_ixj2d4xkj6ca-7 0}.lst-kix\_rjtsao9vofr3-6>li{counter-increment:lst-ctn-kix\_rjtsao9vofr3-6}.lst-kix\_gzze5qyu37i0-8>li{counter-increment:lst-ctn-kix\_gzze5qyu37i0-8}.lst-kix\_rjtsao9vofr3-7>li:before{content:"" counter(lst-ctn-kix\_rjtsao9vofr3-7,lower-latin) ". "}.lst-kix\_rjtsao9vofr3-7>li{counter-increment:lst-ctn-kix\_rjtsao9vofr3-7}.lst-kix\_rjtsao9vofr3-8>li:before{content:"" counter(lst-ctn-kix\_rjtsao9vofr3-8,lower-roman) ". "}ol.lst-kix\_ixj2d4xkj6ca-1{list-style-type:none}ol.lst-kix\_8xt5grgbz7zp-4.start{counter-reset:lst-ctn-kix\_8xt5grgbz7zp-4 0}ol.lst-kix\_ixj2d4xkj6ca-2{list-style-type:none}ol.lst-kix\_ixj2d4xkj6ca-0{list-style-type:none}.lst-kix\_8xt5grgbz7zp-8>li{counter-increment:lst-ctn-kix\_8xt5grgbz7zp-8}.lst-kix\_o04u6rx3d2ow-8>li{counter-increment:lst-ctn-kix\_o04u6rx3d2ow-8}ol.lst-kix\_gzze5qyu37i0-7.start{counter-reset:lst-ctn-kix\_gzze5qyu37i0-7 0}ol.lst-kix\_rjtsao9vofr3-5{list-style-type:none}ol.lst-kix\_o04u6rx3d2ow-1.start{counter-reset:lst-ctn-kix\_o04u6rx3d2ow-1 0}.lst-kix\_rjtsao9vofr3-5>li{counter-increment:lst-ctn-kix\_rjtsao9vofr3-5}ol.lst-kix\_rjtsao9vofr3-6{list-style-type:none}ol.lst-kix\_rjtsao9vofr3-7{list-style-type:none}.lst-kix\_gzze5qyu37i0-6>li{counter-increment:lst-ctn-kix\_gzze5qyu37i0-6}ol.lst-kix\_rjtsao9vofr3-8{list-style-type:none}ol.lst-kix\_rjtsao9vofr3-1{list-style-type:none}ol.lst-kix\_rjtsao9vofr3-2{list-style-type:none}.lst-kix\_rjtsao9vofr3-8>li{counter-increment:lst-ctn-kix\_rjtsao9vofr3-8}ol.lst-kix\_rjtsao9vofr3-3{list-style-type:none}ol.lst-kix\_rjtsao9vofr3-4{list-style-type:none}ol.lst-kix\_8xt5grgbz7zp-1.start{counter-reset:lst-ctn-kix\_8xt5grgbz7zp-1 0}ol.lst-kix\_gzze5qyu37i0-4.start{counter-reset:lst-ctn-kix\_gzze5qyu37i0-4 0}ol.lst-kix\_rjtsao9vofr3-1.start{counter-reset:lst-ctn-kix\_rjtsao9vofr3-1 0}ol.lst-kix\_rjtsao9vofr3-0{list-style-type:none}.lst-kix\_8xt5grgbz7zp-6>li:before{content:"" counter(lst-ctn-kix\_8xt5grgbz7zp-6,decimal) ". "}.lst-kix\_8xt5grgbz7zp-7>li:before{content:"" counter(lst-ctn-kix\_8xt5grgbz7zp-7,lower-latin) ". "}.lst-kix\_8xt5grgbz7zp-8>li:before{content:"" counter(lst-ctn-kix\_8xt5grgbz7zp-8,lower-roman) ". "}.lst-kix\_o04u6rx3d2ow-0>li:before{content:"" counter(lst-ctn-kix\_o04u6rx3d2ow-0,decimal) ". "}ol.lst-kix\_o04u6rx3d2ow-7.start{counter-reset:lst-ctn-kix\_o04u6rx3d2ow-7 0}.lst-kix\_8xt5grgbz7zp-0>li:before{content:"" counter(lst-ctn-kix\_8xt5grgbz7zp-0,decimal) ". "}.lst-kix\_gzze5qyu37i0-0>li:before{content:"" counter(lst-ctn-kix\_gzze5qyu37i0-0,decimal) ". "}.lst-kix\_rjtsao9vofr3-3>li{counter-increment:lst-ctn-kix\_rjtsao9vofr3-3}.lst-kix\_ixj2d4xkj6ca-2>li{counter-increment:lst-ctn-kix\_ixj2d4xkj6ca-2}.lst-kix\_gzze5qyu37i0-1>li:before{content:"" counter(lst-ctn-kix\_gzze5qyu37i0-1,lower-latin) ". "}.lst-kix\_o04u6rx3d2ow-1>li:before{content:"" counter(lst-ctn-kix\_o04u6rx3d2ow-1,lower-latin) ". "}.lst-kix\_o04u6rx3d2ow-0>li{counter-increment:lst-ctn-kix\_o04u6rx3d2ow-0}.lst-kix\_o04u6rx3d2ow-2>li:before{content:"" counter(lst-ctn-kix\_o04u6rx3d2ow-2,lower-roman) ". "}.lst-kix\_8xt5grgbz7zp-5>li:before{content:"" counter(lst-ctn-kix\_8xt5grgbz7zp-5,lower-roman) ". "}ol.lst-kix\_rjtsao9vofr3-4.start{counter-reset:lst-ctn-kix\_rjtsao9vofr3-4 0}.lst-kix\_o04u6rx3d2ow-6>li{counter-increment:lst-ctn-kix\_o04u6rx3d2ow-6}.lst-kix\_8xt5grgbz7zp-4>li:before{content:"" counter(lst-ctn-kix\_8xt5grgbz7zp-4,lower-latin) ". "}.lst-kix\_o04u6rx3d2ow-4>li:before{content:"" counter(lst-ctn-kix\_o04u6rx3d2ow-4,lower-latin) ". "}.lst-kix\_o04u6rx3d2ow-3>li:before{content:"" counter(lst-ctn-kix\_o04u6rx3d2ow-3,decimal) ". "}.lst-kix\_8xt5grgbz7zp-2>li:before{content:"" counter(lst-ctn-kix\_8xt5grgbz7zp-2,lower-roman) ". "}.lst-kix\_8xt5grgbz7zp-7>li{counter-increment:lst-ctn-kix\_8xt5grgbz7zp-7}.lst-kix\_o04u6rx3d2ow-6>li:before{content:"" counter(lst-ctn-kix\_o04u6rx3d2ow-6,decimal) ". "}.lst-kix\_8xt5grgbz7zp-1>li:before{content:"" counter(lst-ctn-kix\_8xt5grgbz7zp-1,lower-latin) ". "}.lst-kix\_8xt5grgbz7zp-3>li:before{content:"" counter(lst-ctn-kix\_8xt5grgbz7zp-3,decimal) ". "}ol.lst-kix\_o04u6rx3d2ow-6.start{counter-reset:lst-ctn-kix\_o04u6rx3d2ow-6 0}.lst-kix\_ixj2d4xkj6ca-3>li{counter-increment:lst-ctn-kix\_ixj2d4xkj6ca-3}.lst-kix\_8xt5grgbz7zp-1>li{counter-increment:lst-ctn-kix\_8xt5grgbz7zp-1}.lst-kix\_o04u6rx3d2ow-5>li:before{content:"" counter(lst-ctn-kix\_o04u6rx3d2ow-5,lower-roman) ". "}ol.lst-kix\_ixj2d4xkj6ca-5.start{counter-reset:lst-ctn-kix\_ixj2d4xkj6ca-5 0}ol.lst-kix\_gzze5qyu37i0-6.start{counter-reset:lst-ctn-kix\_gzze5qyu37i0-6 0}.lst-kix\_rjtsao9vofr3-0>li:before{content:"" counter(lst-ctn-kix\_rjtsao9vofr3-0,decimal) ". "}.lst-kix\_ixj2d4xkj6ca-6>li{counter-increment:lst-ctn-kix\_ixj2d4xkj6ca-6}.lst-kix\_o04u6rx3d2ow-8>li:before{content:"" counter(lst-ctn-kix\_o04u6rx3d2ow-8,lower-roman) ". "}.lst-kix\_rjtsao9vofr3-1>li:before{content:"" counter(lst-ctn-kix\_rjtsao9vofr3-1,lower-latin) ". "}.lst-kix\_o04u6rx3d2ow-7>li:before{content:"" counter(lst-ctn-kix\_o04u6rx3d2ow-7,lower-latin) ". "}.lst-kix\_gzze5qyu37i0-8>li:before{content:"" counter(lst-ctn-kix\_gzze5qyu37i0-8,lower-roman) ". "}.lst-kix\_rjtsao9vofr3-6>li:before{content:"" counter(lst-ctn-kix\_rjtsao9vofr3-6,decimal) ". "}ol.lst-kix\_8xt5grgbz7zp-6.start{counter-reset:lst-ctn-kix\_8xt5grgbz7zp-6 0}ol.lst-kix\_o04u6rx3d2ow-5.start{counter-reset:lst-ctn-kix\_o04u6rx3d2ow-5 0}.lst-kix\_gzze5qyu37i0-2>li:before{content:"" counter(lst-ctn-kix\_gzze5qyu37i0-2,lower-roman) ". "}.lst-kix\_gzze5qyu37i0-4>li:before{content:"" counter(lst-ctn-kix\_gzze5qyu37i0-4,lower-latin) ". "}.lst-kix\_rjtsao9vofr3-5>li:before{content:"" counter(lst-ctn-kix\_rjtsao9vofr3-5,lower-roman) ". "}.lst-kix\_gzze5qyu37i0-3>li:before{content:"" counter(lst-ctn-kix\_gzze5qyu37i0-3,decimal) ". "}ol.lst-kix\_gzze5qyu37i0-5.start{counter-reset:lst-ctn-kix\_gzze5qyu37i0-5 0}.lst-kix\_gzze5qyu37i0-7>li:before{content:"" counter(lst-ctn-kix\_gzze5qyu37i0-7,lower-latin) ". "}ol.lst-kix\_ixj2d4xkj6ca-4.start{counter-reset:lst-ctn-kix\_ixj2d4xkj6ca-4 0}.lst-kix\_rjtsao9vofr3-3>li:before{content:"" counter(lst-ctn-kix\_rjtsao9vofr3-3,decimal) ". "}ol.lst-kix\_rjtsao9vofr3-3.start{counter-reset:lst-ctn-kix\_rjtsao9vofr3-3 0}.lst-kix\_rjtsao9vofr3-4>li:before{content:"" counter(lst-ctn-kix\_rjtsao9vofr3-4,lower-latin) ". "}ol.lst-kix\_8xt5grgbz7zp-0.start{counter-reset:lst-ctn-kix\_8xt5grgbz7zp-0 0}.lst-kix\_gzze5qyu37i0-1>li{counter-increment:lst-ctn-kix\_gzze5qyu37i0-1}.lst-kix\_gzze5qyu37i0-6>li:before{content:"" counter(lst-ctn-kix\_gzze5qyu37i0-6,decimal) ". "}.lst-kix\_gzze5qyu37i0-7>li{counter-increment:lst-ctn-kix\_gzze5qyu37i0-7}ol.lst-kix\_gzze5qyu37i0-8{list-style-type:none}.lst-kix\_rjtsao9vofr3-2>li:before{content:"" counter(lst-ctn-kix\_rjtsao9vofr3-2,lower-roman) ". "}ol.lst-kix\_gzze5qyu37i0-6{list-style-type:none}.lst-kix\_gzze5qyu37i0-4>li{counter-increment:lst-ctn-kix\_gzze5qyu37i0-4}.lst-kix\_gzze5qyu37i0-5>li:before{content:"" counter(lst-ctn-kix\_gzze5qyu37i0-5,lower-roman) ". "}ol.lst-kix\_gzze5qyu37i0-7{list-style-type:none}ol.lst-kix\_8xt5grgbz7zp-3{list-style-type:none}.lst-kix\_ixj2d4xkj6ca-8>li:before{content:"" counter(lst-ctn-kix\_ixj2d4xkj6ca-8,lower-roman) ". "}ol.lst-kix\_8xt5grgbz7zp-4{list-style-type:none}ol.lst-kix\_gzze5qyu37i0-8.start{counter-reset:lst-ctn-kix\_gzze5qyu37i0-8 0}ol.lst-kix\_o04u6rx3d2ow-8{list-style-type:none}ol.lst-kix\_8xt5grgbz7zp-1{list-style-type:none}.lst-kix\_ixj2d4xkj6ca-7>li:before{content:"" counter(lst-ctn-kix\_ixj2d4xkj6ca-7,lower-latin) ". "}ol.lst-kix\_8xt5grgbz7zp-2{list-style-type:none}ol.lst-kix\_rjtsao9vofr3-2.start{counter-reset:lst-ctn-kix\_rjtsao9vofr3-2 0}ol.lst-kix\_8xt5grgbz7zp-0{list-style-type:none}.lst-kix\_rjtsao9vofr3-0>li{counter-increment:lst-ctn-kix\_rjtsao9vofr3-0}.lst-kix\_ixj2d4xkj6ca-4>li:before{content:"" counter(lst-ctn-kix\_ixj2d4xkj6ca-4,lower-latin) ". "}.lst-kix\_ixj2d4xkj6ca-5>li:before{content:"" counter(lst-ctn-kix\_ixj2d4xkj6ca-5,lower-roman) ". "}.lst-kix\_o04u6rx3d2ow-4>li{counter-increment:lst-ctn-kix\_o04u6rx3d2ow-4}ol.lst-kix\_8xt5grgbz7zp-7{list-style-type:none}.lst-kix\_ixj2d4xkj6ca-6>li:before{content:"" counter(lst-ctn-kix\_ixj2d4xkj6ca-6,decimal) ". "}ol.lst-kix\_8xt5grgbz7zp-8{list-style-type:none}ol.lst-kix\_8xt5grgbz7zp-5{list-style-type:none}ol.lst-kix\_o04u6rx3d2ow-0.start{counter-reset:lst-ctn-kix\_o04u6rx3d2ow-0 0}ol.lst-kix\_8xt5grgbz7zp-6{list-style-type:none}.lst-kix\_ixj2d4xkj6ca-0>li:before{content:"" counter(lst-ctn-kix\_ixj2d4xkj6ca-0,decimal) ". "}.lst-kix\_rjtsao9vofr3-1>li{counter-increment:lst-ctn-kix\_rjtsao9vofr3-1}.lst-kix\_ixj2d4xkj6ca-1>li:before{content:"" counter(lst-ctn-kix\_ixj2d4xkj6ca-1,lower-latin) ". "}.lst-kix\_gzze5qyu37i0-2>li{counter-increment:lst-ctn-kix\_gzze5qyu37i0-2}ol.lst-kix\_o04u6rx3d2ow-1{list-style-type:none}ol.lst-kix\_ixj2d4xkj6ca-0.start{counter-reset:lst-ctn-kix\_ixj2d4xkj6ca-0 0}.lst-kix\_8xt5grgbz7zp-4>li{counter-increment:lst-ctn-kix\_8xt5grgbz7zp-4}ol.lst-kix\_o04u6rx3d2ow-0{list-style-type:none}ol.lst-kix\_o04u6rx3d2ow-3{list-style-type:none}ol.lst-kix\_o04u6rx3d2ow-3.start{counter-reset:lst-ctn-kix\_o04u6rx3d2ow-3 0}.lst-kix\_ixj2d4xkj6ca-3>li:before{content:"" counter(lst-ctn-kix\_ixj2d4xkj6ca-3,decimal) ". "}ol.lst-kix\_o04u6rx3d2ow-2{list-style-type:none}ol.lst-kix\_o04u6rx3d2ow-5{list-style-type:none}.lst-kix\_ixj2d4xkj6ca-2>li:before{content:"" counter(lst-ctn-kix\_ixj2d4xkj6ca-2,lower-roman) ". "}ol.lst-kix\_o04u6rx3d2ow-4{list-style-type:none}ol.lst-kix\_o04u6rx3d2ow-7{list-style-type:none}.lst-kix\_o04u6rx3d2ow-3>li{counter-increment:lst-ctn-kix\_o04u6rx3d2ow-3}ol.lst-kix\_o04u6rx3d2ow-6{list-style-type:none}ol.lst-kix\_8xt5grgbz7zp-8.start{counter-reset:lst-ctn-kix\_8xt5grgbz7zp-8 0}.lst-kix\_gzze5qyu37i0-0>li{counter-increment:lst-ctn-kix\_gzze5qyu37i0-0}.lst-kix\_gzze5qyu37i0-3>li{counter-increment:lst-ctn-kix\_gzze5qyu37i0-3}.lst-kix\_8xt5grgbz7zp-2>li{counter-increment:lst-ctn-kix\_8xt5grgbz7zp-2}.lst-kix\_ixj2d4xkj6ca-0>li{counter-increment:lst-ctn-kix\_ixj2d4xkj6ca-0}.lst-kix\_o04u6rx3d2ow-5>li{counter-increment:lst-ctn-kix\_o04u6rx3d2ow-5}ol.lst-kix\_gzze5qyu37i0-0.start{counter-reset:lst-ctn-kix\_gzze5qyu37i0-0 0}.lst-kix\_o04u6rx3d2ow-2>li{counter-increment:lst-ctn-kix\_o04u6rx3d2ow-2}.lst-kix\_8xt5grgbz7zp-5>li{counter-increment:lst-ctn-kix\_8xt5grgbz7zp-5}ol.lst-kix\_ixj2d4xkj6ca-3.start{counter-reset:lst-ctn-kix\_ixj2d4xkj6ca-3 0}ol.lst-kix\_8xt5grgbz7zp-5.start{counter-reset:lst-ctn-kix\_8xt5grgbz7zp-5 0}ol.lst-kix\_rjtsao9vofr3-5.start{counter-reset:lst-ctn-kix\_rjtsao9vofr3-5 0}ol.lst-kix\_ixj2d4xkj6ca-6.start{counter-reset:lst-ctn-kix\_ixj2d4xkj6ca-6 0}.lst-kix\_ixj2d4xkj6ca-8>li{counter-increment:lst-ctn-kix\_ixj2d4xkj6ca-8}.lst-kix\_rjtsao9vofr3-2>li{counter-increment:lst-ctn-kix\_rjtsao9vofr3-2}ol.lst-kix\_rjtsao9vofr3-8.start{counter-reset:lst-ctn-kix\_rjtsao9vofr3-8 0}ol.lst-kix\_o04u6rx3d2ow-2.start{counter-reset:lst-ctn-kix\_o04u6rx3d2ow-2 0}ol.lst-kix\_rjtsao9vofr3-7.start{counter-reset:lst-ctn-kix\_rjtsao9vofr3-7 0}ol.lst-kix\_8xt5grgbz7zp-2.start{counter-reset:lst-ctn-kix\_8xt5grgbz7zp-2 0}ol.lst-kix\_ixj2d4xkj6ca-2.start{counter-reset:lst-ctn-kix\_ixj2d4xkj6ca-2 0}.lst-kix\_o04u6rx3d2ow-1>li{counter-increment:lst-ctn-kix\_o04u6rx3d2ow-1}ol.lst-kix\_rjtsao9vofr3-0.start{counter-reset:lst-ctn-kix\_rjtsao9vofr3-0 0}.lst-kix\_o04u6rx3d2ow-7>li{counter-increment:lst-ctn-kix\_o04u6rx3d2ow-7}ol.lst-kix\_gzze5qyu37i0-3.start{counter-reset:lst-ctn-kix\_gzze5qyu37i0-3 0}.lst-kix\_ixj2d4xkj6ca-7>li{counter-increment:lst-ctn-kix\_ixj2d4xkj6ca-7}.lst-kix\_rjtsao9vofr3-4>li{counter-increment:lst-ctn-kix\_rjtsao9vofr3-4}.lst-kix\_gzze5qyu37i0-5>li{counter-increment:lst-ctn-kix\_gzze5qyu37i0-5}ol.lst-kix\_o04u6rx3d2ow-8.start{counter-reset:lst-ctn-kix\_o04u6rx3d2ow-8 0}ol.lst-kix\_ixj2d4xkj6ca-5{list-style-type:none}ol.lst-kix\_ixj2d4xkj6ca-6{list-style-type:none}ol.lst-kix\_gzze5qyu37i0-2.start{counter-reset:lst-ctn-kix\_gzze5qyu37i0-2 0}ol.lst-kix\_ixj2d4xkj6ca-3{list-style-type:none}ol.lst-kix\_ixj2d4xkj6ca-8.start{counter-reset:lst-ctn-kix\_ixj2d4xkj6ca-8 0}ol.lst-kix\_ixj2d4xkj6ca-4{list-style-type:none}ol.lst-kix\_ixj2d4xkj6ca-7{list-style-type:none}ol.lst-kix\_ixj2d4xkj6ca-8{list-style-type:none}ol.lst-kix\_rjtsao9vofr3-6.start{counter-reset:lst-ctn-kix\_rjtsao9vofr3-6 0}li.li-bullet-0:before{margin-left:-18pt;white-space:nowrap;display:inline-block;min-width:18pt}.lst-kix\_8xt5grgbz7zp-0>li{counter-increment:lst-ctn-kix\_8xt5grgbz7zp-0}.lst-kix\_8xt5grgbz7zp-3>li{counter-increment:lst-ctn-kix\_8xt5grgbz7zp-3}.lst-kix\_ixj2d4xkj6ca-1>li{counter-increment:lst-ctn-kix\_ixj2d4xkj6ca-1}.lst-kix\_ixj2d4xkj6ca-4>li{counter-increment:lst-ctn-kix\_ixj2d4xkj6ca-4}.lst-kix\_8xt5grgbz7zp-6>li{counter-increment:lst-ctn-kix\_8xt5grgbz7zp-6}ol.lst-kix\_8xt5grgbz7zp-3.start{counter-reset:lst-ctn-kix\_8xt5grgbz7zp-3 0}ol.lst-kix\_ixj2d4xkj6ca-1.start{counter-reset:lst-ctn-kix\_ixj2d4xkj6ca-1 0}ol{margin:0;padding:0}table td,table th{padding:0}.c2{margin-left:36pt;padding-top:16pt;text-indent:-18pt;padding-bottom:4pt;line-height:1.5;page-break-after:avoid;orphans:2;widows:2;text-align:justify}.c1{margin-left:36pt;padding-top:0pt;padding-left:0pt;padding-bottom:0pt;line-height:1.0;orphans:2;widows:2;text-align:justify}.c8{color:#434343;font-weight:700;text-decoration:none;vertical-align:baseline;font-size:14pt;font-family:"Arial";font-style:normal}.c6{color:#000000;font-weight:700;text-decoration:none;vertical-align:baseline;font-size:18pt;font-family:"Arial";font-style:italic}.c10{padding-top:0pt;padding-bottom:0pt;line-height:1.0;orphans:2;widows:2;text-align:justify;height:14pt}.c11{padding-top:24pt;padding-bottom:0pt;line-height:1.5;page-break-after:avoid;orphans:2;widows:2;text-align:justify}.c9{padding-top:36pt;padding-bottom:6pt;line-height:1.0;page-break-after:avoid;orphans:2;widows:2;text-align:left}.c0{color:#000000;font-weight:400;text-decoration:none;vertical-align:baseline;font-size:14pt;font-family:"Times New Roman";font-style:normal}.c5{padding-top:10pt;padding-bottom:0pt;line-height:1.0;orphans:2;widows:2;text-align:justify}.c7{background-color:#ffffff;max-width:538.6pt;padding:28.3pt 28.3pt 28.3pt 28.3pt}.c3{padding:0;margin:0}.c4{background-color:#f4cccc}.title{padding-top:0pt;color:#000000;font-size:26pt;padding-bottom:3pt;font-family:"Times New Roman";line-height:1.0;page-break-after:avoid;orphans:2;widows:2;text-align:justify}.subtitle{padding-top:0pt;color:#666666;font-weight:500;padding-left:5pt;border-left-color:#6aa84f;font-size:10pt;padding-bottom:0pt;line-height:1.0;page-break-after:avoid;border-left-width:1.5pt;background-color:#fff2cc;border-left-style:solid;font-family:"Roboto Mono";orphans:2;widows:2;text-align:justify}li{color:#000000;font-size:14pt;font-family:"Times New Roman"}p{margin:0;color:#000000;font-size:14pt;font-family:"Times New Roman"}h1{padding-top:20pt;color:#000000;font-weight:700;font-size:24pt;padding-bottom:6pt;font-family:"Arial";line-height:1.0;page-break-after:avoid;orphans:2;widows:2;text-align:justify}h2{padding-top:36pt;color:#000000;font-weight:700;font-size:18pt;padding-bottom:6pt;font-family:"Arial";line-height:1.0;page-break-after:avoid;font-style:italic;orphans:2;widows:2;text-align:left}h3{padding-top:24pt;color:#434343;font-weight:700;font-size:14pt;padding-bottom:0pt;font-family:"Arial";line-height:1.5;page-break-after:avoid;orphans:2;widows:2;text-align:justify}h4{padding-top:14pt;color:#666666;font-size:14pt;padding-bottom:4pt;font-family:"Arial";line-height:1.5;page-break-after:avoid;font-style:italic;orphans:2;widows:2;text-align:justify}h5{padding-top:12pt;color:#666666;font-size:11pt;padding-bottom:4pt;font-family:"Times New Roman";line-height:1.0;page-break-after:avoid;orphans:2;widows:2;text-align:justify}h6{padding-top:12pt;color:#666666;font-size:11pt;padding-bottom:4pt;font-family:"Times New Roman";line-height:1.0;page-break-after:avoid;font-style:italic;orphans:2;widows:2;text-align:justify}

Программа экзамена
------------------

### по дисциплине “Операционные системы семейства UNIX и сетевые технологии”

Билет на экзамене по дисциплине «Операционные системы семейства UNIX и сетевые технологии» состоит из двух теоретических и одного практического вопроса. Экзамен проводится письменно. Каждое из трех заданий экзамена оценивается в двадцать баллов.

При ответе на теоретические вопросы студент должен продемонстрировать не только достаточный уровень компетентности в рамках рассматриваемого вопроса, но и опыт личной работы в рамках темы вопроса. Оценивается демонстрация самоподготовки студента, выражающаяся в собственных суждениях, сведениях, почерпнутых в ходе самостоятельного изучения вопроса в литературе, технической документации, электронных ресурсах, форумах и так далее.

При решении практических заданий студент должен представить текст скрипта на языке программирования Python либо скриптового языка программирования bash, пояснения алгоритма работы, а также описание всех параметров, которые принимает скрипт (если таковые присутствуют) и описание формата вывода скрипта (если таковой присутствует). В связи с письменным проведением экзамена, при проверке правильности решения практического задания, в первую очередь будет оцениваться грамотность алгоритма, знание команд Linux и Bash, некритичные опечатки, приводящие к неработоспособности скрипта допускаются.

### Теоретические вопросы к экзамену

1.  Понятие операционной системы, выполняемые ей функции.
2.  Порядок загрузки компьютера и операционной системы.
3.  История развития ОС.
4.  Семейство операционных систем UNIX. Философия UNIX.
5.  Сравнительная характеристика Linux и Windows.
6.  Понятие системного вызова операционной системы.
7.  Понятие виртуализации. Виртуальные машины.
8.  Основные компоненты операционной системы. Разделение функций.
9.  Понятие файловой системы. Функции, виды, характеристики.
10.  Физические и логические диски. Разбиение жесткого диска для установки Linux.
11.  Стандартная иерархия каталогов Linux.
12.  Понятие ядра операционной системы. Пространство ядра и пользовательское пространство.
13.  Командный интерпретатор операционной системы.
14.  Управление оперативной памятью в современных ОС. Виртуальная память.
15.  Работа ОС с внешними устройствами. Понятие драйвера устройства.
16.  Многозадачность современных операционных систем.
17.  Графический и текстовый интерфейс взаимодействия с ОС.
18.  Источники установки программных приложений. Программные репозитории.
19.  Способы установки программ  в Linux.
20.  Процессы в Linux. Функции, организация, управление.
21.  Жизненный цикл процесса операционной системы.
22.  Основные команды Linux для управления файлами.
23.  Основные команды Linux для управления каталогами.
24.  Основные команды Linux для управления файловыми системами.
25.  Понятие пакета в Linux. Менеджеры пакетов.
26.  Основные команды Linux для управления пакетами.
27.  Основные команды Linux для управления процессами.
28.  Типы файлов в Linux. Ссылки.
29.  Основные команды для управления текстовыми потоками.
30.  Основные команды для просмотра и редактирования текстовых файлов.
31.  Регулярные выражения.
32.  Встроенные и внешние команды bash.
33.  Основные конфигурационные файлы Linux.
34.  Командный интерпретатор bash. Структура команды.
35.  Bash. Переменные и типы.
36.  Bash. Условия.
37.  Bash. Циклы.
38.  Bash. Функции.
39.  Переменные окружения в bash.
40.  Основные команды Linux для управления пользователями и группами.
41.  Суперпользователь root. Характеристика, особенности, функции, опасность.
42.  Система прав доступа Linux. Структура и смысл прав доступа.
43.  Организация хранения паролей пользователей в Linux.
44.  Основные команды Linux для управления правами доступа.
45.  Понятие компьютерных сетей. Общие принципы, организация.
46.  Понятие сетевого ресурса. Классификация.
47.  Семейство сетевых протоколов TCP/IP.
48.  Адресация компьютеров в сети. IP, MAC адреса.
49.  Удаленный доступ к командной строке. Протокол SSH.
50.  SSH-ключи. Назначение, использование, генерация.
51.  Понятие виртуальной сети. Виды виртуальных сетевых компонентов.
52.  Трансляция сетевых адресов. Виды NAT.
53.  Использование Linux для разработки. Стандартные программные средства.
54.  Интерпретатор Python. Использование, версии. Понятие виртуального окружения, настройка, использование.
55.  Структура проекта на Python. Организация модулей. Файл зависимостей.
56.  Системы контроля версий. Примеры, назначение, общие понятия.
57.  Общий алгоритм работы с СКВ Git. Инициализация репозитория, добавление файлов, коммиты.
58.  Работа с ветвлением в Git. Назначение веток. Создание, переключение, объединение веток. Разрешение конфликтов слияния.
59.  Работа с удаленными репозиториями. Клонирование и форк репозиториев. Отправка и получение изменений в удаленный репозиторий.
60.  Современные методологии работы с Git в командном проекте. GitFlow.
61.  Понятие сетевого сокета. Применение, виды, схема взаимодействия.
62.  Блокирующие операции при обмене через сокеты. Возможные ошибки. Таймауты.
63.  Транспортные протоколы TCP и UDP. Принципы работы, сравнение.
64.  Клиент-серверное взаимодействие.
65.  Реализация сокетов в языке Python. Модуль socket.
66.  Понятие программного потока. Процессы и потоки.
67.  Асинхронное программирование. Основные понятия. Параллелизм и конкуррентность.
68.  Блокирующие и неблокирующие операции.
69.  Алгоритмы, ограниченные процессором и вводом-выводом. Основные характеристики, особенности выполнения и распараллеливания.
70.  Особенности реализации многопоточности в Python. Модуль threading.
71.  Особенности организации многопроцессорной программы в Python. Модуль multiprocessing.
72.  Асинхронное программирование в Python. Использование asyncio.
73.  Параллельное программирование. Достоинства и недостатки.
74.  Понятие потокобезопасности. Причины, проблематика, способы обеспечения.
75.  Алгоритм выполнения многопоточной программы. Блокировка потоков.
76.  Доступ к общим ресурсам в многопоточной программе. Механизмы блокировки ресурсов модуля threading.
77.  Работа с файловой системой в Python. Основные операции.
78.  Понятие веб-технологий. Основные характеристики, история, назначение.
79.  Программное обеспечение, используемое для веб-технологий. Виды, назначение, примеры.
80.  Понятие URL: назначение, применение, состав.
81.  Понятие веб-сервера. Цели, принцип работы.
82.  Протокол HTTP. Принцип работы, назначение, основные понятия.
83.  Настройка веб-сервера. Основные конфигурационные файлы, понятия.
84.  Виртуальные хосты. Применение, настройка.
85.  Понятие прокси-сервера. Настройка сервера nginx.

86.  Основные принципы криптографии. Шифры. Исторические шифры.
87.  Симметричное шифрование. Примеры алгоритмов, общая схема, виды.
88.  Асимметричное шифрование. Примеры алгоритмов, общая схема, преимущества и недостатки.
89.  Алгоритмы хэширования. Примеры, назначение.
90.  Протокол TLS/SSL. Общая схема взаимодействия, назначение.
91.  Понятие SSL-сертификата. Назначение. Самоподписанные сертификаты. Центры сертификации.
92.  FTP-сервер. Назначение, общая схема работы. Обеспечение безопасности.
93.  Настройка FTP-сервера в Linux. Основные понятия, конфигурационные файлы.
94.  Email-сервер. Назначение, общая схема работы. Обеспечение безопасности.
95.  Настройка Email-сервера в Linux. Основные понятия, конфигурационные файлы.
96.  Основные принципы мониторинга сетевых служб. Мониторинг четырех золотых сигналов.
97.  Прикладные интерфейсы программирования. Назначение, виды, реализация.
98.  Развертывание приложений на удаленном сервере. Основные процессы. Понятие тестового и рабочего программных окружений.
99.  Управление конфигурациями. Основные понятия, назначение. Примеры систем.
100.  Контейнеризация программных приложений. Основные понятия, использование.

### Примерные практические задания к экзамену

1.  Напишите программу, которая создает нить. Родительская и вновь созданная нити должны распечатать десять строк текста.
2.  Напишите простой эхо-сервер, использующий неблокирующие сокеты и клиент к нему.
3.  Напишите простой многопоточный загрузчик URL. Список URL скрипт принимает как аргументы командной строки.
4.  Реализуйте простой HTTP-клиент. Он принимает один параметр командной строки - URL. Клиент делает запрос по указанному URL и выдает тело ответа на терминал как текст.
5.  Напишите программу, которая вычисляет число Пи при помощи ряда Эйлера. Количество потоков программы должно определяться параметром командной строки.
6.  Дана функция calculate(x, y). Напишите программу, которая создает пул из 5 процессов и распределяет в этом пуле вычисление функции на промежутке х от 0 до 1 с шагом 0,1. у равняется 2 всегда.
7.  Напишите программу, которая проверяет все числа от 0 на простоту и выводит простые числа на экран по мере нахождения. Числа должны проверяться в различных потоках (или процессах, по выбору студента) Программа должна работать до тех пор, пока ее не остановит пользователь.
8.  Напишите программу, которая обходит все файлы в директории, переданной ей как параметр и выводит на экран имена тех, чей размер задан как второй параметр. Реализовать рекурсивный обход поддиректорий.
9.  Напишите программу, которая выводит на экран список номеров открытых портов на данной машине. Использовать команду netstat.
10.  Напишите программу, которая копирует файл с удаленного хоста в текущую папку по SSH. Имя файла и адрес хоста принимать как параметры.
11.  Сценарий должен вывести (на stdout) все числа, делящиеся на 12, в диапазоне от первого параметра до последнего. Если параметры заданы некорректно, скрипт должен вывести сообщение.
12.  Сценарий должен имитировать работу лототрона -- извлекать 5 случайных неповторяющихся чисел в диапазоне 1 - 50. Сценарий должен предусматривать как вывод на stdout, так и запись чисел в файл, кроме того, вместе с числами должны выводиться дата и время генерации данного набора.
13.  Напишите сценарий, который находил бы корни "квадратного " уравнения, вида: Ax^2 + Bx + C = 0. Сценарий должен получать коэффициенты уравнения A, B и C, как аргументы командной строки, и выводить корни. Если корней нет, вывод должен быть пустым.
14.  Написать скрипт, который выведет всех потомков процесса по его PID.
15.  Напишите скрипт, который и считает кол-во измененных в течении последних 3 дней файлов из каталога, переданного как параметр и выводит на экран.
16.  Написать скрипт, который выведет информацию о топ10 процессов по потреблению оперативной памяти.
17.  Написать скрипт, который выведет все файлы в домашней директории пользователя, измененные за последнюю неделю.
18.  Напишите сценарий, который принимает как аргументы список программ и устанавливает их в текущую систему. Сделайте возможность передать список программ через текстовый файл.
19.  Напишите скрипт, выводящий сообщение в случае, если в файле /etc/hosts есть записи относящиеся к адресам отличным от 127.0.0.1.
20.  Разработать сценарий, который ведёт в файле /tmp/run.log журнал запусков. При каждом запуске сценария в конец журнала должна добавляться строка с датой и временем запуска сценария, в стандартный вывод - фраза "Hello", в stderr - количество предыдущих запусков программы. Убедиться в правильности работы программы и выводе различных сообщений в различные потоки вывода.