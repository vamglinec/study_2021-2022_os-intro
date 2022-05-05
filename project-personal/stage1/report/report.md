---
## Front matter
title: "Отчёт по первому этапу индивидуального проекта"
subtitle: "*дисциплина: оперционные сиситемы*"
author: "Мглинец Варвара Александровна"

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
lot: true # List of tables
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
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Размещение на Github pages заготовки для персонального сайта.

 - Установить необходимое программное обеспечение.
 - Скачать шаблон темы сайта.
 - Разместить его на хостинге git.
 - Установить параметр для URLs сайта.
 - Разместить заготовку сайта на Github pages.


# Шаг 1.Установка необходимого программного обеспечения

Скачиваем необходимую нам версию программного обеспечения и открываем в загрузках. Разархивируем файл в папку, зыходим в папку и вырезаем из нее файл hugo. После этого в домашнем каталоге создаем папку с именем bin и помещаем файл hugo туда.

![Скачивание ПО](file:///afs/.dk.sci.pfu.edu.ru/home/v/a/vamglinec/%D0%A0%D0%B0%D0%B1%D0%BE%D1%87%D0%B8%D0%B9%20%D1%81%D1%82%D0%BE%D0%BB/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%B2%202022-04-29%2017-26-53.png){ #fig:001 width=70% }

![Разархивирование](file:///afs/.dk.sci.pfu.edu.ru/home/v/a/vamglinec/%D0%A0%D0%B0%D0%B1%D0%BE%D1%87%D0%B8%D0%B9%20%D1%81%D1%82%D0%BE%D0%BB/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%B2%202022-04-29%2017-27-18.png){ #fig:002 width=70% }

![Создание папки](file:///afs/.dk.sci.pfu.edu.ru/home/v/a/vamglinec/%D0%A0%D0%B0%D0%B1%D0%BE%D1%87%D0%B8%D0%B9%20%D1%81%D1%82%D0%BE%D0%BB/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%B2%202022-04-29%2017-27-34.png){ #fig:003 width=70% }


# Шаг 2. Скачивание шаблона темы сайта.

Переходим по ссылке на нужный репозиторий и нажимаем "использовать этот шаблон". Создаем репозиторий blog.

![Необходимый шаблон](file:///afs/.dk.sci.pfu.edu.ru/home/v/a/vamglinec/%D0%A0%D0%B0%D0%B1%D0%BE%D1%87%D0%B8%D0%B9%20%D1%81%D1%82%D0%BE%D0%BB/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%B2%202022-04-29%2017-29-02.png){ #fig:004 width=70% }



# Шаг 3. Клонирование репозитория.

Копируем ссылку, заходим в консоль и выполняем клонирование в blog при помощи команды git clone.

# Шаг 4. Размещаем шаблон на хостинге гит.


# Шаг 5. Устанавливаем параметр для URLs сайта.


# Шаг 6. Размещаем заготовку сайта на Github pages.


# Вывод

Я разместила на Github pages заготовки для персонального сайта.


# Список литературы{.unnumbered}

::: {#refs}
:::
