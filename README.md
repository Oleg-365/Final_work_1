# Задание:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами. 

# Описание алгоритма решения:
Объявляется два массива: начальный и вторый такой же длины. Потом используем метод в котором цикл соразмерный длине массива, внутри цикла осуществляем проверку условия (<=3), если "да" элемент первого массива заносится в count элемент второго массива. Переменная count, чтобы поочередно перемещать из первого массива во второй, и чтобы потом не было пробелов. После присвоения, увеличивается переменная count на 1 и возвращается к циклу for, в котором i увеличивается на 1. И так проверка осуществляется до конца.

Блок-схема метода представлена в папке Scheme c расширением jpeg.

Алгоритм решения задания по пути Task_1/Program.cs