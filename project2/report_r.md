---
## Front matter
title: "Индивидуальный проект №2"
subtitle: "Добавление к сайту данных о себе"
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

Научиться менять фотографию-аватар, изменять личные данные, добавлять посты.

# Выполнение лабораторной работы

Изменил фотографию-аватар (рис. [-@fig:001]).

![Фотография-аватар](image/1.png){#fig:001 width=70%}

Редактирую файл с личной информацией (рис. [-@fig:002]).

![Файл с личной информаицей](image/2.png){#fig:002 width=70%}

Взял ссылку на локальный сайт (рис. [-@fig:003]).

![Ссылка на локальный сайт](image/3.png){#fig:003 width=70%}

Показываю начальную страницу сайта с измененными данными (рис. [-@fig:004]).

![Начальная страница](image/3_5.png){#fig:004 width=70%}

Создаю пост last_week через терминал (рис. [-@fig:005]).

![Пост last_week](image/4.png){#fig:005 width=70%}

Редактирую пост last_week (рис. [-@fig:006]).

![Редактирование поста](image/5.png){#fig:006 width=70%}

Показываю созданный пост (рис. [-@fig:007]).

![Созданный пост last_week](image/6.png){#fig:007 width=70%}

Создаю пост Git (рис. [-@fig:008]).

![Создание поста](image/7.png){#fig:008 width=70%}

Редактирую пост Git (рис. [-@fig:009]).

![Редактирование поста](image/8.png){#fig:009 width=70%}

Показываю созданный пост (рис. [-@fig:010]).

![Созданный пост Git](image/9.png){#fig:010 width=70%}

# Выводы

Научился менять фотографию-аватар, изменять личные данные, добавлять посты.

# Список литературы{.unnumbered}

::: {#refs}
:::
