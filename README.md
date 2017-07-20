# NET.S.2017.01.Daniluk.05
1.	Разработать класс, позволяющий выполнять вычисления НОД по алгоритму Евклида для двух, трех и т.д. целых чисел (http://en.wikipedia.org/wiki/Euclidean_algorithm , https://habrahabr.ru/post/205106/ ). Методы класса помимо вычисления НОД должны определять значение времени, необходимое для выполнения расчета. Добавить к разработанному классу методы, реализующие алгоритм Стейна (бинарный алгоритм Евклида) для расчета НОД двух, трех и т.д. целых чисел (http://en.wikipedia.org/wiki/Binary_GCD_algorithm ). Методы должны также  определять значение времени, необходимое для выполнения расчетов. Разработать unit-тесты для тестирования методов данного типа.
1.1. Выполнить рефакторинг класса (с целью сокращения повторного кода) в алгоритмах Евклида (для рефакторинга использовать делегаты, рефакторинг возможен только в случае, когда все метод находятся в одном классе!). Интерфейс класса измениться не должен.

2.	Реализовать метод расширения для получения двоичного представления вещественного числа двойной точности в формате IEEE 754 (https://habrahabr.ru/post/112953/ ). Разработать модульные тесты.
3.  Разработать неизменяемый класс Polynomial (полином) для работы с многочленами степени  от одной переменной вещественного типа (в качестве внутренней структуры для хранения коэффициентов использовать sz-массив). Для разработанного класса
-	переопределить необходимые методы класса Object;
-	перегрузить операции, допустимые для работы с многочленами (исключая деление многочлена на многочлен). 
-	Разработать unit-тесты.
