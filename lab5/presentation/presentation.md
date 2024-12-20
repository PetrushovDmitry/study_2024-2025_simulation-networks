---
## Front matter
lang: ru-RU
title: Лабораторная работа 5
author:
  - Петрушов Дмитрий Сергеевич 1032212287
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 2024

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

# Цель работы

  Основной целью работы является получение навыков проведения интерактивных экспериментов в среде 
Mininet по исследованию параметров сети, связанных с потерей, дублированием, изменением порядка 
и повреждением пакетов при передаче данных. Эти параметры влияют на производительность протоколов и сетей.


# Выполнение работы

## Начало выполнения

![Исправление прав запуска X-соединения в виртуальной машине mininet](image/1.png){ #fig:001 width=100% height=100% }

## Начало выполнения  

![Отображение информации их сетевых интерфейсов и IP-адресов](image/2.png){ #fig:002 width=100% height=100% }

## Добавление первого правила на h1  

![Добавление 10% потерь пакетов на хосте h1](image/4.png){ #fig:003 width=100% height=100% }

## Проверка  

![Проверка](image/5.png){ #fig:004 width=100% height=100% }

## Добавление правила на h2

![Добавление 10% потерь пакетов на хосте h2](image/6.png){ #fig:005 width=100% height=100% }

## Проверка 

![Проверка](image/7.png){ #fig:006 width=100% height=100% }

## Добавление на узле h1 коэффициента потери пакетов 50%

![Добавление на узле h1 коэффициента потери пакетов 50%](image/9.png){ #fig:007 width=100% height=100% }

## Проверка

![Проверка](image/10.png){ #fig:008 width=100% height=100% }

## Добавление на узле h1 0.01% повреждения пакетов

![Добавление на узле h1 0.01% повреждения пакетов](image/12.png){ #fig:009 width=100% height=100% }


## Проверка конфигурации с помощью инструмента iPerf3 для проверки повторных передач

![Проверка конфигурации с помощью инструмента iPerf3 для проверки повторных передач](image/14.png){ #fig:010 width=100% height=100% }

## Добавление на узле h1 нового правила

![Добавление на узле h1 нового правила](image/15.png){ #fig:011 width=100% height=100% }

## Проверка

![Проверка](image/16.png){ #fig:012 width=100% height=100% }

## Добавление на узле h1 правила с дублированием 50% пакетов

![Добавление на узле h1 правила с дублированием 50% пакетов](image/17.png){ #fig:013 width=100% height=100% }

## Проверка

![Проверка](image/18.png){ #fig:014 width=100% height=100% }

## Последующая работа

![Создание каталога simple-drop и дальнейшее его открытие](image/19.png){ #fig:014 width=100% height=100% }

## Последующая работа

![Создание скрипта для эксперимента](image/20.png){ #fig:015 width=100% height=100% }

## Последующая работа

![Создание Makefile и помещение в него скрипта](image/21.png){ #fig:016 width=100% height=100% }

## Вывод

В ходе выполнения лабораторной работы получили навыки проведения интерактивных экспериментов в 
среде Mininet по исследованию параметров сети, связанных с потерей, дублированием, изменением порядка 
и повреждением пакетов при передаче данных.