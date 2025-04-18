---
## Front matter
lang: ru-RU
title: "Презентация к лабораторной работе №5"
subtitle: "Дисциплина: Операционные системы"
author:
  - Долгаев Е. С.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 14 марта 2025

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
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="30%"}

  * Долгаев Евгений Сергеевич
  * студент
  * Российский университет дружбы народов
  * [1132246827@rudn.ru](mailto:1132246827@rudn.ru)
  * <https://github.com/eugerne/dotfiles.git>

:::
::::::::::::::

# Вводная часть

## Актуальность

- Улучшение рабочей среды

## Объект и предмет исследования

- Рабочая среда для выполнения лабораторных работ

## Цели и задачи

- Настроить рабочую среду

# Лабораторная работа

## Содержание исследования

### Менеджер паролей pass

#### Установка

Установим менеджер паролей pass.

![Установка менеджера паролей](image/1.png){width=40%}

## Содержание исследования

#### Настройка

Выведем список GPG-ключей.

![Список GPG-ключей](image/2.png){width=40%}

## Содержание исследования

Инициализируем хранилище.

![Инициализация хранилища](image/3.png){width=40%}

## Содержание исследования

Создадим структуру git.

![Создание стуктуры git](image/4.png){width=40%}

## Содержание исследования

#### Настройка интерфейса с броузером

Для взаимодействия с броузером используется интерфейс native messaging, кроме того нужно установить плагин к браузеру.

![Плагин для браузера](image/7.png){width=40%}

## Содержание исследования

![Интерфейс native messaging](image/8.png){width=40%}

## Содержание исследования

![Интерфейс native messaging](image/9.png){width=40%}

## Содержание исследования

#### Сохранение пароля

Добавим новый пароль в файл parol в каталоге passwords.

![Новый пароль](image/10.png){width=40%}

## Содержание исследования

Отобразим пароль для указанного имени файла.

![Отображение пароля](image/11.png){width=40%}

## Содержание исследования

Заменим существующий пароль.

![Замена пароля](image/12.png){width=40%}

## Содержание исследования

### Управление файлами конфигурации

### Дополнительное программное обеспечение

Установим дополнительное программное обеспечение.

![Установка доп. ПО](image/13.png){width=40%}

## Содержание исследования

Установите шрифты.

![Установка шрифтов](image/14.png){width=40%}

## Содержание исследования

![Установка шрифтов](image/15.png){width=20%}

## Содержание исследования

![Установка шрифтов](image/16.png){width=40%}

## Содержание исследования

#### Установка

Установим бинарный файл. Скрипт определяет архитектуру процессора и операционную систему и скачивает необходимый файл.

![Установка бинарного файла](image/17.png){width=40%}

## Содержание исследования

#### Создание собственного репозитория с помощью утилит

Будем использовать утилиты командной строки для работы с github. Создадим свой репозиторий для конфигурационных файлов на основе шаблона. 

![Создание репозитория](image/18.png){width=40%}

## Содержание исследования

#### Подключение репозитория к своей системе

Инициализируем chezmoi с нашим репозиторием dotfiles.

![Инициализация](image/19.png){width=40%}

## Содержание исследования

Проверим, какие изменения внесёт chezmoi в домашний каталог, запустив.

![Проверка](image/20.png){width=20%}

## Содержание исследования

#### Использование chezmoi на нескольких машинах

Сделаем всё то же самое, что и в прошлом шаге на второй машине. Поскольку OC Linux Fedora установлена у меня на виртуальной машине, поэтому в качестве второй машины я выбрал свою осноную ОС (Linux Ubuntu).

![Инициализация](image/21.png){width=40%}

## Содержание исследования

![Проверка](image/22.png){width=40%}

## Содержание исследования

#### Настройка новой машины с помощью одной команды

Можно установить свои dotfiles на новый компьютер с помощью одной команды.

![Другой способ](image/23.png){width=60%}

## Содержание исследования

#### Ежедневные операции c chezmoi

Ивлечём изменения из репозитория и применить их одной командой.

![Извлечение изменений](image/24.png){width=60%}

## Содержание исследования

Извлечём последние изменения из своего репозитория и посмотрим, что изменится, фактически не применяя изменения. 

![Извлечение изменений](image/25.png){width=60%}

## Содержание исследования

Применим изменения.

![Применение изменений](image/26.png){width=60%}

## Содержание исследования

Включим автоматическую фиксацию и отправку изменений, добавив в файл конфигурации ~/.config/chezmoi/chezmoi.toml следующее.

![Автоматическая фиксация и отправка](image/27.png){width=40%}

## Результаты

- Таким образом, мы получаем настроенную рабочую среду.

