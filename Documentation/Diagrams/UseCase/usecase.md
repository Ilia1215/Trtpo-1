﻿# Варианты использования
---

![Диаграмма Варианты использования](https://github.com/MilenaVysotskaya650502/Calculator/blob/master/Documentation/Diagrams/UseCase/use_case.png)

# Содержание
1 [Актёры](#1) <br>
2 [Варианты использования](#2) <br>
  2.1 [Матричный калькулятор](#2.1) <br>
  2.2 [Основной калькулятор](#2.2) <br>
  2.3 [Битовый калькулятор](#2.3) <br>
  2.4 [Конвертер чисел](#2.4) <br>
  2.5 [Конвертер формул в формат Latex](#2.4) <br>
  
<a name="1"/>

# 1 Актёры

| Актёр | Описание |
|:--|:--|
| Пользователь | Человек, использующий данное приложение |

<a name="2"/>

# 2 Варианты использования

<a name="2.1"/>

## 2.1 Матричный калькулятор

**Описание.** Вариант использования "Матричный калькулятор" дает пользователю возможность расчета операций над матрицами(сложение, вычитание, умножение, деление, транспонирование, взятие обратной матрицы, умножение на число).

**Основной поток.**
1. Приложение отображает пользователю рабочую зону матричного калькулятора.
2. Пользователь вводит исходные данные матриц.
3. Пользователь нажимает кнопку соответстующей операции.
4. Приложение проверяет корректность введенных данных. В случае некорректности выполняется альтернативный поток А1.
5. Приложение подсчитывает результат.
6. Приложение выводит результат в рабочую зону графического интерфейса калькулятора.
7. Вариант использования завершается;

**Альтернативный поток А1.**
1. Приложение выводит сообщение о необходимости проверить введенные данные.
2. Возврат к п.1 основного потока;

<a name="2.2"/>

## 2.2 Основной калькулятор

**Описание.** Вариант использования "Основной калькулятор" дает пользователю возможность расчета основных алгебраических операций над числами(сложение, вычитание, умножение, деление, факториал, возведение в степень, корень квадратный, синус, косинус).

**Основной поток.**
1. Приложение отображает пользователю рабочую зону основного калькулятора.
2. Пользователь вводит исходное выражение.
3. Пользователь нажимает кнопку "="
4. Приложение проверяет корректность введенных данных. В случае некорректности выполняется альтернативный поток А2.
5. Приложение подсчитывает результат.
6. Приложение выводит результат в рабочую зону графического интерфейса калькулятора.
7. Вариант использования завершается;

**Альтернативный поток А2.**
1. Приложение выводит сообщение о необходимости проверить введенные данные.
2. Возврат к п.1 основного потока;

<a name="2.3"/>

## 2.3 Битовый калькулятор

**Описание.** Вариант использования "Битовый калькулятор" дает пользователю возможность расчета основных бинарных операций над двоичными числами(and, or, xor, not).

**Основной поток.**
1. Приложение отображает пользователю рабочую зону бинарного калькулятора.
2. Пользователь вводит исходные бинарные числа.
3. Пользователь выбирает вид операции.
4. Пользователь нажимает кнопку "расчитать".
5. Приложение проверяет корректность введенных данных. В случае некорректности выполняется альтернативный поток А3.
6. Приложение подсчитывает результат.
7. Приложение выводит результат в рабочую зону графического интерфейса калькулятора.
8. Вариант использования завершается;

**Альтернативный поток А3.**
1. Приложение выводит сообщение о необходимости проверить введенные данные.
2. Возврат к п.1 основного потока;

<a name="2.4"/>

## 2.4 Конвертер чисел

**Описание.**  Вариант использования "Конвертер чисел" дает пользователю возможность конвертации чисел из одной системы счисление(двоичной, десятичной, восьмеричной, шестнадцатеричной) в остальные доступные.

**Основной поток.**
1. Приложение отображает пользователю рабочую зону конвертера чисел.
2. Пользователь выбирает формат исходного числа.
3. Пользователь нажимает кнопку "перевести"
4. Приложение проверяет корректность введенных данных. В случае некорректности выполняется альтернативный поток А4.
5. Приложение подсчитывает результат.
6. Приложение выводит результат в рабочую зону графического интерфейса калькулятора.
7. Вариант использования завершается;

**Альтернативный поток А4.**
1. Приложение выводит сообщение о необходимости проверить введенные данные.
2. Переход на п.1 основного поток;

## 2.5 Конвертер формул в формат Latex

**Описание.**  Вариант использования "Конвертер формул в формат Latex" дает пользователю возможность конвертации формул в формат языка Latex.

**Основной поток.**
1. Приложение отображает пользователю рабочую зону конвертера формул.
2. Пользователь вводит исходную формулу.
3. Пользователь нажимает кнопку "перевести"
4. Приложение проверяет корректность введенных данных. В случае некорректности выполняется альтернативный поток А5.
5. Приложение подсчитывает результат.
6. Приложение выводит результат в рабочую зону графического интерфейса калькулятора.
7. Вариант использования завершается;

**Альтернативный поток А5.**
1. Приложение выводит сообщение о необходимости проверить введенные данные.
2. Переход на п.1 основного поток;

