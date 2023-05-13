---
## Front matter
title: "Индивидуальный проект. Этап 5. Презентация."
subtitle: "Добавление проектов, постов"
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

Сделать записи для персональных проектов, сделать пост по прошедшей неделе и пост о языках научного программирования.

# Выполнение лабораторной работы

Создал проект на тему криптовалюты (рис. [-@fig:1])

![Создание проекта](image/1.png){#fig:1 width = 70%}

Написал пост по прошедшей неделе (рис. [-@fig:2])

![Написание поста о прошедшей неделе](image/2.png){#fig:2 width = 70%}

Написал пост о научных языках программирования (рис. [-@fig:3])

![Написание поста о научных языках программирования](image/3.png){#fig:3 width = 70%}

# Выводы

Сделал записи для персональных проектов, сделал пост по прошедшей неделе и пост о языках научного программирования.

# Список литературы{.unnumbered}

::: {#refs}
:::
