---
## Front matter
title: "Индивидуальный проект №1"
subtitle: "Создание шаблона сайта"
author: "Козлов Всеволод Павлович"

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

Научиться создавать шаблон академического сайта.

# Задание

Создать шаблон собственного академического сайта.

# Выполнение лабораторной работы

Установил hugo_extended с удаленного репозитория (рис. [-@fig:001])

![Установка hugo](image/tar_d.png){#fig:001 width 70%}

Перенес hugo в папку bin (рис. [-@fig:002])

![Перенос hugo в bin](image/bin.png){#fig:002 width 70%}

Создание репозитория по шаблону starter-hugo (рис. [-@fig:003])

![Создание репозитория](image/rep_cr.png){#fig:003 width 70%}

Клонирую репозиторий (рис. [-@fig:004])

![Клонирование репозитория](image/4clone.png){#fig:004 width 70%}

Установил golang (рис. [-@fig:005])

![Установка golang](image/5gol.png){#fig:005 width 70%}

Расположим hugo в каталоге пользователся (рис. [-@fig:006])

![Располгаем hugo в каталоге пользователя](image/6user.png){#fig:006 width 70%}

Удаляем каталог /public (рис. [-@fig:007])

![Удаление каталога /public](image/7del.png){#fig:007 width 70%}

Откроем шаблон сайта с помощью ~/bin/hugo server (рис. [-@fig:008])

![Просмотр шаблона сайта](image/8server.png){#fig:008 width 70%}

Создадим репозиторий сайта (рис. [-@fig:009])

![Создание репозитория сайта](image/9repnew.png){#fig:009 width 70%}

Склонируем репозиторий сайта (рис. [-@fig:010])

![Клонирование репозитория сайта](image/10clone.png){#fig:010 width 70%}

Создал ветку main и файл README.me (рис. [-@fig:011])

![Сохдание ветки main и файла README.me](image/11_main_read.png){#fig:011 width 70%}

Комментируем public/, чтобы избежать ошибки игнорирования (рис. [-@fig:012])

![Комментирование public/](image/12comment.png){#fig:012 width 70%}

Добавляем существующий репозиторий в индекс (рис. [-@fig:013])

![Добавление репозитория в индекс](image/13_public.png){#fig:013 width 70%}

Произведем автоматическое создание файлов в public с помощью ~/bin/hugo, начнем создание коммита (рис. [-@fig:014])

![Автоматическое создание файлов в public](image/14commit.png){#fig:014 width 70%}

Отправим коммит в удаленный репозиторий (рис. [-@fig:015])

![Отправка коммита в удаленный репозиторий](image/15push.png){#fig:015 width 70%}

Демонстрация работоспособности сайта (рис. [-@fig:016])

![Скриншот сайта](image/16dem.png){#fig:016 width 70%}

# Выводы

Научился создавать шаблон академического сайта.

# Список литературы{.unnumbered}

::: {#refs}
:::
