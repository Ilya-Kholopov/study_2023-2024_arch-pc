---
## Front matter
title: "ОТЧЕТ ПО ЛАБОРАТОРНОЙ РАБОТЕ №3"
subtitle: "дисциплина: Архитектура компьютера"
author: "Холопов Илья Алексеевич"

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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

# Выполнение работы

Откроем терминал, перейдем в каталог курса, сформированный при выполнении лабораторной работы №2 и обновим локальный репозиторий (рис. @fig:001).

![Переход в каталог курса и обновление репозитория](image/1.png){#fig:001 width=70%}

Перейдем в каталог с шаблоном отчета по лабораторной работе № 3 и проведем компиляцию шаблона с помощью Makefile (рис. @fig:002).

![Компиляция шаблона](image/2.png){#fig:002 width=70%}

Удалим полученные файлы с использование Makefile и проверим, что docx и pdf файлы были удалены (рис. @fig:003).

![Удаление файлов с помощью Makefile](image/3.png){#fig:003 width=70%}

Откроем файл report.md с помощью текстового редактора gedit и проанализируем файл (рис. @fig:004).

![Содержимое файла report.md](image/4.png){#fig:004 width=70%}

Заполним отчет по лабораторным работам №2 и №3 с использованием Makefile и загрузим файлы на Github (рис. @fig:005-@fig:007).

![Создание отчета по лабораторной работе №2](image/5.png){#fig:005 width=70%}

![Создание отчета по лабораторной работе №3](image/6.png){#fig:006 width=70%}

![Внесение изменений в репозиторий](image/7.png){#fig:007 width=70%}

# Выводы

В результате выполнения лабораторной работы была освоена процедура оформления отчетов с помощью легковесного языка разметки Markdown, были созданы отчеты по лабораторным работам №2 и №3 с помщью языка разметка Markdown.

