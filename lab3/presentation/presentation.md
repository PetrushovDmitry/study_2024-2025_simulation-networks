---
## Front matter
lang: ru-RU
title: Лабораторная работа 3
author:
  - Петрушов Дмитрий, 1032212287
institute:
  - Российский университет дружбы народов, Москва, Россия
date: "2024"

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---



# Выполнение

## Загрузка всего нужного

![Установка](image/1.png){#fig:001 width=70%}

## Внесение изменений в скрипт

![изменения](image/4.png){#fig:002 width=70%}

## Проверка

![изменения](image/6.png){#fig:003 width=70%}

## Внесение изменений в файл lab_iperf3.py

![.](image/9.png){#fig:004 width=70%}

## Написание Makefile

![Makefile](../report/image/11.png){#fig:005 width=70%}

## Проверка

![Проверка](../report/image/12.png){#fig:006 width=70%}




## Вывод

Мы познакомились с инструментом для измерения пропускной способности сети в режиме реального времни - iperf3, а также получили навыки проведения воспроизводимого эксперимента по измерению пропускной способности моделируемой сери в среде Mininet.
