---
## Front matter
lang: ru-RU
title: Структура научной презентации
subtitle: Простейший шаблон
author:
  -  Абд эль хай М.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 07 марта 2024
mainfont: "Times New Roman" 
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

Познакомится с принципами планирования локальной сети организации

# Задание

1. Используя графический редактор (например, Dia), требуется повторить схемы L1, L2, L3, а также сопутствующие им таблицы VLAN, IP-адресов и портов подключения оборудования планируемой сети.

2. Рассмотренный выше пример планирования адресного пространства сети базируется на разбиении сети 10.128.0.0/16 на соответствующие подсети. Требуется сделать аналогичный план адресного пространства для сетей 172.16.0.0/12 и 192.168.0.0/16 с соответствующими схемами сети и сопутствующими таблицами VLAN, IP-адресов и портов подключения оборудования.

2. При выполнении работы необходимо учитывать соглашение об именовании 


# Выполнение лабораторной работы

Схема планируемой сети с указанием типов и номеров портов подключения устройств, соответствующая физическому уровню модели OSI (L1), будет иметь вид, изображённый на рис 3.1.

![Физические устройства сети с номерами портов (Layer 1)](../report/image/net1L1.png){#fig:001 width=100%}

## Сеть1 Таблица портов

![net1](../report/image/net1Tablesports.png){#fig:002 width=100%}

## Сеть1 Диаграм l2

![net1 Диаграм l2](../report/image/net1L2.png){#fig:003 width=100%}

## Сеть1 Таблица VLAN

![net1](../report/image/net1Tablesvlan.png){#fig:004 width=100%}

## Сеть1 Диаграм l3

![net1 Диаграм l3](../report/image/net1L3.png){#fig:005 width=100%}

## Сеть1 Таблица IP

![net1 ](../report/image/net1Tablesip.png){#fig:006 width=100%}

## Сеть2 Диаграм l1

![net2 Диаграм l1](../report/image/net2L1.png){#fig:007 width=100%}

## Сеть2 Таблица портов

![net2 ](../report/image/net2Tablesports.png){#fig:008 width=100%}

## Сеть2 Диаграм l2

![net2 Диаграм l2](../report/image/net2L2.png){#fig:009 width=100%}
 
## Сеть2 Таблица VLAN

![net2 ](../report/image/net2Tablesvlan.png){#fig:010 width=100%}

## Сеть2 Диаграм l3

![net2 Диаграм l3](../report/image/net2L3.png){#fig:011 width=100%}

## Сеть2 Таблица IP

![net2 ](../report/image/net2Tablesip.png){#fig:012 width=100%}

## Сеть3 Диаграм l1

![net3 ](../report/image/net3L1.png){#fig:013 width=100%}




# Выводы

Здесь кратко описываются итоги проделанной работы.
