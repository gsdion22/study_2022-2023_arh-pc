---
## Front matter
title: "Лабораторная работы №1. "
subtitle: "Установка и конфигурация операционной системы на виртуальную машину"
author: |
        ДИОН ГОНССАН СЕДРИК МИШЕЛ
  
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
## Цель работы

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

## Настройка каталога для виртуальных машин
## Настройка хост-клавиши
## Создание виртуальной машины

Все эти этапы были сделаны в прошлом семестре, результат этих пунктов был показан на видео

# После установки
# Обновления и повышение комфорта работы

!![Получил права супер-пользователя и обновил пакеты](image/01.png){ #fig:001 width=80% }

![dnf install tmux mc](image/02.png){ #fig:002 width=80% }

# Автоматическое обновление

![Установил программное обеспечение для автоматических обновлений](image/03.png){ #fig:003 width=80%}

# Отключение SELinux

![Заменил значение в config](image/04.png){ #fig:005 width=80% }

# Установка драйверов для VirtualBox

![Установка пакета DKMS](image/05.png){ #fig:006 width=80%}

![Установка драйверов](image/07.png){ #fig:007 width=80%}

# Настройка раскладки клавиатуры

![Отредактирвал конфигурационный файл](image/08.png){ #fig:008 width=80%}

# Установка имени пользователя и названия хоста

![имени пользователя и названия хоста](image/09.png){ #fig:009 width=80%}
              Все было установлено сразу правильно

# Установка программного обеспечения для создания документации

![Установил pandoc:](image/10.png){ #fig:010 width=80% }

![Установил texlive:](image/11.png){ #fig:011 width=80% }

# Домашнее Задание



![Версия ядра Linux ](image/12.png){ #fig:012 width=80% }

![Частота процессора, Модель процессора, Объём доступной оперативной памяти, Тип обнаруженного гипервизора,Тип файловой системы корневого раздела](image/14.png){ #fig:014 width=80% }


# Контрольные Вопросы

1. Какую информацию содержит учётная запись пользователя?  

Имя пользователя, зашифрованный пароль пользователя, идентификационный номер пользователя, идентификационный номер группы пользователя, домашний каталог пользователя, командный интерпретатор пользователя. 

2. Укажите команды терминала и приведите примеры: – для получения справки по команде; – для перемещения по файловой системе; – для просмотра содержимого каталога; – для определения объёма каталога; – для создания / удаления каталогов / файлов; – для задания определённых прав на файл / каталог; – для просмотра истории команд. 

mv
ls
du 
mkdir 
chmod 
history

3. Что такое файловая система? Приведите примеры с краткой характеристикой. 

Файловая система — это часть операционной системы, назначение которой состоит в 
том, чтобы обеспечить пользователю удобный интерфейс при работе с данными, 
хранящимися на диске, и обеспечить совместное использование файлов несколькими 
пользователями и процессами. 
Примеры файловых систем: 

• Ext2, Ext3, Ext4 или Extended Filesystem – стандартная файловая система для Linux. 
• JFS или Journaled File System была разработана в IBM для AIX UNIX и 
использовалась в качестве альтернативы для файловых систем ext. Она используется 
там, где необходима высокая стабильность и минимальное потребление ресурсов. 
• ReiserFS – была разработана намного позже, но в качестве альтернативы ext3 с 
улучшенной производительностью и расширенными возможностями. 
• XFS – это высокопроизводительная файловая система. Преимущества: высокая 
скорость работы с большими файлами, отложенное выделение места, увеличение 
разделов на лету и незначительный размер служебной информации. [3] 

4. Как посмотреть, какие файловые системы подмонтированы в ОС?  

С помощью команды mount. 

5. Как удалить зависший процесс? 

С помощью команды kill.

# Выводы

Целью данного занятия было приобретение практических навыков по установке операционной системы на виртуальную машину, настройке минимальных служб, необходимых для последующей работы.

:::

## {.Standout}
                    Спасибо за винимание
