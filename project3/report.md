---
## Front matter
title: "Индивидуальный проект. Этап 3"
subtitle: "Добавление информации о владельце сайта"
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

Научиться добавлять информацию о навыках, опыте и достижениях владельца сайта. Создать пост и прошедшей неделе, а также пост на одну из выбранных тем.

# Выполнение лабораторной работы

Заранее создал пост last_week2, получил локальную ссылку на сайт (рис. [-@fig:001]).

![Создание ветви, получение локальной ссылки на сайт](image/1.png){#fig:001 width=70%}

Отредактировал блок skills (рис. [-@fig:002]).

![Редактирование блока skills](image/2.png){#fig:002 width=70%}

Отредактировал блок experience (рис. [-@fig:003]).

![Редактирование блока experience](image/3.png){#fig:003 width=70%}

Отредактировал блок accomplishments (рис. [-@fig:004]).

![Редактирование блока accompishments](image/4.png){#fig:004 width=70%}

Добавил информацию в пост last_week2 (рис. [-@fig:005]).

![Добавлние информации в пост last_week2](image/5.png){#fig:005 width=70%}

Создал пост markup о легковесных языках разметки (рис. [-@fig:006]).

![Создание поста markup](image/6.png){#fig:006 width=70%}

Добавил информацию в пост markup (рис. [-@fig:007]).

![Добавлние информации в пост markup](image/7.png){#fig:007 width=70%}

# Выводы

Научился добавлять информацию о навыках, опыте и достижениях владельца сайта. Создал пост и прошедшей неделе, а также пост на одну из выбранных тем.

# Список литературы{.unnumbered}

::: {#refs}
:::
