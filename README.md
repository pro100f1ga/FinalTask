# Задача: Фильтрация массива строк

Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Описание программы

Создаются два массива строк: `array1` и `array2`. Массив `array1` инициализируется строками фиксированной длины.

### Функции

#### SecondArrayWithIF

Функция `SecondArrayWithIF` принимает два массива строк в качестве аргументов. Внутри функции происходит итерация по элементам массива `array1`. Если длина строки в текущем элементе меньше или равна 3, то эта строка копируется в соответствующий элемент массива `array2`. По завершении цикла выводится массив `array2`.

#### PrintArray

Функция `PrintArray` принимает массив строк и выводит его элементы на консоль.

### Использование

1. Запуск программы.
2. Ввод массива строк либо использование массива, заданного на старте.
3. Вызывается функция `SecondArrayWithIF` с передачей ей массивов `array1` и `array2`.
4. Вызывается функция `PrintArray` с аргументом `array2` для вывода содержимого полученного массива.

## Алгоритм представлен в приложении "Блок-схема.jpg"