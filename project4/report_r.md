---
## Front matter
title: "Индивидуальный проект. Этап 4."
subtitle: "Social links"
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

Добавить сслыки на youtube, rutube, guthub. Написать пост о прошедшей неделе и пост на одну из выбранных тем.

# Выполнение лабораторной работы

Перешел в ~/work/blog и добавил два поста (рис. [-@fig:001]).

![Добавление постов](image/1.png){#fig:001 width=70%}

Добавил Social links (рис. [-@fig:002]).

![Добавление Social links](image/2.png){#fig:002 width=70%}

Отредактировал пост last_week3 (рис. [-@fig:003]).

![Редактирование поста last_week3](image/3.png){#fig:003 width=70%}

Отредактировал пост last_week3 (рис. [-@fig:004]).

![Редактирование поста bibliographic_list](image/4.png){#fig:004 width=70%}

# Выводы

Добавил сслыки на youtube, rutube, guthub. Написал пост о прошедшей неделе и пост о работе со списком литературы.

# Список литературы{.unnumbered}

::: {#refs}
:::
