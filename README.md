# [ИДБ-17-06](https://github.com/stankin/design-part-1/wiki/list-idb-17-06) Волков Алексей

## Домашнее задание по [семинару 1](https://github.com/stankin/design-part-1/wiki/sem1), [семинару 2](https://github.com/stankin/design-part-1/wiki/sem2)

## [Отчет]() по лабораторным работам 1-3

## Домашние задания по [семинарам 3-4]()

## Отчет по лабораторным работам 4-6

## Рефераты: [разработанный](https://github.com/stankin/design-part-1/wiki/exam01-1) и проверенный


# Отчет о лабораторных работах

# Cтудент группы ИДБ-17-06 Волков А.С.

## Лабораторная работа №1

Сборщик собирает велосипед.

IDF0 диаграмма:

![A](https://github.com/alexvolk228/VolkovAlexey/blob/master/lab1/idf0.png?raw=true)

Сборщик должен собрать велосипед в соответствии с планом, используя детали и инструменты. 

Диаграмма классов:

![A](https://github.com/alexvolk228/VolkovAlexey/blob/master/lab1/uml-class.png?raw=true)


Диаграмма прецедентов:

![A](https://github.com/alexvolk228/VolkovAlexey/blob/master/lab1/uml-prec.png?raw=true)

## Лабораторная работа №2

На диаграмме изображён процесс сборки велосипеда. 

Контекстная IDF0 диаграмма:
![A](https://github.com/alexvolk228/VolkovAlexey.github.io/blob/master/lab2/idf01.png?raw=true)

Подуровень IDF0 диаграммы:
![A](https://github.com/alexvolk228/VolkovAlexey.github.io/blob/master/lab2/idf02.png?raw=true)

A1 Отдел качества получает на вход детали. На выходе получаются детали, соответствующие стандартам.

A2 Сборщик, получив детали, согласовывает заказ с планом. На выходе получается дата и срок сборки.

A3 Определившись с датой и сроком сборки сборщик собирает веллосипед. На выходе получается собранный велосипед.

A4 Получив собранный велосипед механик настраивает переключатели. На выходе получается готовый к эксплуатации велосипед.

DFD диаграмма:
![A](https://github.com/alexvolk228/VolkovAlexey.github.io/blob/master/lab2/dfd_1.png?raw=true)

Сборщик получает детали, соответствующие стандартам, и c помощью системы работы с заказами формирует заказ в БД.

Диаграмма прецедентов:

![A](https://github.com/alexvolk228/VolkovAlexey.github.io/blob/master/lab2/uml-2.png?raw=true)

## Лабораторная работа №3

Диаграмма последовательности

[Текст](https://github.com/alexvolk228/VolkovAlexey.github.io/blob/master/lab3/diag_posled.txt) и [рисунок](https://github.com/alexvolk228/VolkovAlexey.github.io/blob/master/lab3/diagr_posled_png.png?raw=true) диаграммы последовательности. 

![A](https://github.com/alexvolk228/VolkovAlexey.github.io/blob/master/lab3/diagr_posled_png.png?raw=true)

Менеджер создаёт полный заказ (с датой, описанием и сроком сборки) сборщику через веб-приложение, а сборщик через интерфейс веб-приложения на своей строне принимает заказ.

ER-диаграмма

[Текст](https://github.com/alexvolk228/VolkovAlexey.github.io/blob/master/lab3/diag_class.txt) и [рисунок](https://github.com/alexvolk228/VolkovAlexey.github.io/blob/master/lab3/diag_class_png.png?raw=true) диаграммы классов. 

![A](https://github.com/alexvolk228/VolkovAlexey.github.io/blob/master/lab3/diag_class_png.png?raw=true)

Заказ - это запись в базе данных, которая относится к информационным потокам, и состоит из: даты, описания, срока сборки.
