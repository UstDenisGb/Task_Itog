# Итоговая задача
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами  

## Описание решения

1. Задается изначальный массив.
2. Объявляется второй массив такой же длины. 
3. Инициируется метод, в котором задается цикл, действующий пока он меньше длины массива.
4. Внутри цикла - проверка условия ( <=3 ), если да - элемент первого массива заносится в count элемент второго массива. После присвоения count увеличивается на 1 и возвращается к циклу for в котором i увеличивается на 1.
