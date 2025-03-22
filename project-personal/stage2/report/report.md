---
## Front matter
title: "Отчет по индивидуальному проекту. Этап 2"
subtitle: "*Дисциплина: Архитектура компьютера*"
author: "Долгаев Евгений НММбд-01-24"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Модифицировать сайт научного работника.

# Задание

* Добавить к сайту данные о себе.
* Сделать пост по прошедшей неделе.
* Добавить пост на тему по выбору.

# Выполнение лабораторной работы

Добавим необходимые данные на наш сайт (рис. [-@fig:001], [-@fig:002], [-@fig:003]).

![Данные](image/1.png){#fig:001 width=70%}

![Данные](image/3.png){#fig:002 width=70%}

![Данные](image/2.png){#fig:003 width=70%}

Далее добавим два поста (рис. [-@fig:004], [-@fig:005], [-@fig:006], [-@fig:007]).: 

1) О прошедшей неделе
2) На выбранную тему

![Пост](image/4.png){#fig:004 width=70%}

![Пост](image/5.png){#fig:005 width=70%}

![Пост](image/6.png){#fig:006 width=70%}

![Пост](image/7.png){#fig:007 width=70%}

# Выводы

Таким образом, мы получили сайт с информацией о себе и несколькими новыми постами.

# Список литературы{.unnumbered}

::: {#refs}
:::
