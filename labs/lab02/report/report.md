---
## Front matter
title: "ОТЧЕТ ПО ЛАБОРАТОРНОЙ РАБОТЕ №2"
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

Целью работы является изучить идеологию и применение средств контроля версий. Приобрести практические навыки по работе с системой git.

# Выполнение работы

Создадим учетную запись на сайте https://github.com (рис. @fig:001).

![Создание учетной записи](image/1.png){#fig:001 width=70%}

Теперь настроим git (имя, email и др.). Результат представлен на рисунке @fig:002.

![Настройка параметров git](image/2.png){#fig:002 width=70%}

Для последующей идентификации на сервере репозиториев сгенерируем приватный и открытый ssh-ключи добавим открытый ключ в учетную запись (рис. @fig:003 и @fig:004).

![Генерация ssh-ключей](image/3.png){#fig:003 width=70%}

![Добавление открытого ssh-ключа в учетную запись](image/4.png){#fig:004 width=70%}

Создадим каталог ~/work/study/2023-2024/«Архитектура компьютера». Процесс создания отображен на рисунке @fig:005.

![Создание структуры каталогов](image/5.png){#fig:005 width=70%}

Создадим репозиторий study_2023-2024_arch-pc, используя шаблон https://github.com/yamadharma/course-directory-student-template (рис. @fig:006).

![Создание репозитория на основе шаблона](image/6.png){#fig:006 width=70%}

Перейдем в каталог курса и клонируем созданный репозиторий (рис. @fig:007).

![Клонирование репозитория](image/7.png){#fig:007 width=70%}

Перейдем в каталог курса, удалим, создадим необходимые файлы и внесем изменения на сервер (рис. @fig:008).

![Внесение изменений в репозиторий](image/8.png){#fig:008 width=70%}

# Выводы

В результате выполнения лабораторной работы были изчены идеология и применение средств контроля версий, приобретены практические навыки по работе с системой git.
