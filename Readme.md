# Контрольная работа
## Цель:

***Написатьпрограмму, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами***

### Описание контрольной работы: 

* Объявляется два массива: начальный и вторый такой же длины. 
* Дальше метод, в котором цикл соответсвует размер длине массива, внутри цикла проверка условия ( <=3 символа), если (Yes) элемент первого массива заносится в count элемент второго массива. 
* Переменная count чтобы поочередно закидывать из первого массива во второй. 
* После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором ( i ) увеличивается на 1. И так проверяется до конца.