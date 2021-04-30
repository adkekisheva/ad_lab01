---
# Front matter
lang: ru-RU
title: Отчёт лабораторной работы № 3"
subtitle: "Markdown"
author: "Кекишева Анастасия Дмитриевна"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

Сделать отчёт по предыдущей лабораторной работе в формате Markdown.

# Выполнение лабораторной работы

![](im/01.jpg){ #fig:001 width=70% }

Клонируем репозиторий с шаблоном и на его основе оформляем отчёт в файле с расширением .md, и командой make создала docx, pdf. 

![](im/06.png){ #fig:001 width=70% }

Я ознакомилась с языком разметки и используя этот язык оформила отчёт к второй лабораторной. Например, что #- это заголовок, ##- заголовок второй степени, 2 звёздочки **слово** выделяют слово жирны и т.к.

![](im/03.png){ #fig:001 width=70% }
![](im/04.png){ #fig:001 width=70% }

Далее, командой make командой make создала docx, pdf. И отправила всё на github.


![](im/02.png){ #fig:001 width=70% }
![](im/05.png){ #fig:001 width=70% }

Результат

# Выводы
Я познакомилась с языком разметки Markdown и оформила отчёт по предыдущей лабораторной работы.
