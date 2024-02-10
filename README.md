# Парадигмы программирования и языки парадигм

## Урок 1. Императивное и декларативное программирование на практике ##

Kаноническая задача сортировки списка

**Задача №1**
Дан список целых чисел numbers. Необходимо написать в императивном стиле процедуру для сортировки числа в списке в порядке убывания. Можно использовать любой алгоритм сортировки.

![Изображение](https://github.com/BanShee-new/Programming_paradigms/blob/main/Screenshots/scr_1.png "Императивный стиль")

**Задача №2**
Написать точно такую же процедуру, но в декларативном стиле

![Изображение](https://github.com/BanShee-new/Programming_paradigms/blob/main/Screenshots/scr_2.png "Декларативный стиль")

## Урок 2. Структурное и процедурное программирование на практике ##

Таблица умножения

Условие: На вход подается число n.
Задача: Написать скрипт в любой парадигме, который выводит на экран таблицу умножения всех чисел от 1 до n.
Обоснуйте выбор парадигм.

**Пример вывода:**
> 1 * 1 = 1
> 1 * 2 = 2
> 1 * 3 = 3
> 1 * 4 = 4
> 1 * 5 = 5
> 1 * 6 = 6
> ...
> 1 * 9 = 9

## Урок 3. ООП на практике ##

Крестики-нолики

**Контекст:** Вероятнее всего, вы с детства знакомы с этой игрой. Пришло время реализовать её. Два игрока по очереди ставят крестики и нолики на игровое поле. Игра завершается когда кто-то победил, либо наступила ничья, либо игроки отказались играть.

**Задача:** Написать игру в “Крестики-нолики”. Можете использовать любые парадигмы, которые посчитаете наиболее подходящими. Можете реализовать доску как угодно - как одномерный массив или двумерный массив (массив массивов). Можете использовать как правила, так и 
 ардкод, на своё усмотрение. Главное, чтобы в игру можно было поиграть через терминал с вашего компьютера.

 ## Урок 4. Функциональное программирование ##

Корреляция

**Контекст:** *Корреляция* - статистическая мера, используемая для оценки связи между двумя случайными величинами.

**Ваша задача:** Написать скрипт для расчета корреляции Пирсона между двумя случайными величинами (двумя массивами). Можете использовать любую парадигму, но рекомендую использовать функциональную, т.к. в этом примере она значительно упростит вам жизнь.

**Формула корреляции Пирсона:**

![Изображение](https://github.com/BanShee-new/Programming_paradigms/blob/main/Screenshots/scr_3.png "Формула корреляции Пирсона")

## Урок 5. Логическое программирование ##

Сумма элементов списка

**Контекст:** Мы уже видели множество решений этой задачи в различных стилях. Пришло время решить её с помощью логической парадигмы.

**Ваша задача:** Написать программу на языке Prolog для вычисления суммы элементов списка. На вход подаётся целочисленный массив. На выходе - сумма элементов массива. 

**Пример на языке Python в функциональной парадигме:**

![Изображение](https://github.com/BanShee-new/Programming_paradigms/blob/main/Screenshots/scr_4.png "Функциональная парадигма на языке Python")

## Урок 6. Парадигмы программирования на практике. Подведение итогов курса ##

**Контекст:** Предположим, что мы хотим найти элемент в массиве (получить его индекс). Мы можем это сделать просто перебрав все элементы. Но что, если массив уже отсортирован? В этом случае можно использовать бинарный поиск. Принцип прост: сначала берём элемент находящийся посередине и сравниваем с тем, который мы хотим найти. Если центральный элемент больше нашего, рассматриваем массив слева от центрального, а если больше - справа и повторяем так до тех пор, пока не найдем наш элемент.

**Ваша задача:** Написать программу на любом языке в любой парадигме для бинарного поиска. На вход подаётся целочисленный массив и число. На выходе - индекс элемента или -1, в случае если искомого элемента нет в массиве 

![Изображение](https://github.com/BanShee-new/Programming_paradigms/blob/main/Screenshots/scr_4.png "Бинарный поиск")
