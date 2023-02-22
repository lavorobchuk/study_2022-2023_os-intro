---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 1"
author: "Воробчук Лилия Андреевна"

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

Цель данного этапа индивидуального проекта - приобрести практические навыки создания заготовки персонального сайта.


# Выполнение лабораторной работы

1. Скачиваю файл hugo_extended_0.110.0_Linux-64bit.tar.gz (рис. @fig:001)

![файл](image/1.png){#fig:001 width=70%}

2. Копирую файл hugo в папку bin(рис. @fig:002)

![папка bin](image/2.png){#fig:002 width=70%}

3. Cоздаю репозиторий blog (рис. @fig:003)

![новый репозиторий](image/3.png){#fig:003 width=70%}

4. Удаляю public в mc

5. Cоздаю еще один репозиторий lavorobchuk.github.io(рис. @fig:004)

![очень новый репозиторий](image/3.png){#fig:004 width=70%}

6. Гит клонирую новый репозиторий

7. Создаю main ветку (рис. @fig:005)

![переключение на ветку main](image/4.png){#fig:005 width=70%}

8. Подключение репозитория к папке public (рис. @fig:006)

![подключение](image/5.png){#fig:006 width=70%}

9. Исправление ошибки в mc (рис. @fig:007)

![устранено.](image/6.png){#fig:007 width=70%}

10. Командой bin hugo cоздаю в папке файлы 

11. Пушу на гитхаб созданные файлы (рис. @fig:008) (рис. @fig:009)

![терминал](image/7.png){#fig:008 width=70%}

![гитхаб](image/8.png){#fig:009 width=70%}

12. Мой сайт (рис. @fig:010)

![сайт](image/9.png){#fig:010 width=70%}


# Вывод

В ходе выполнения данной лабораторной работы я приобрела практические навыки создания заготовки персонального сайта.

