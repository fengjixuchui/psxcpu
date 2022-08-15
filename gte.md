# GTE

= Обзор =

Вкратце основные моменты:

* GTE это кастомный сопроцессор COP2, который производит геометрические вычисления над векторами и матрицами
* Содержит 32 регистра данных (data registers) и 32 регистра управления (control registers)
* Инструкции GTE выполняются много тактов и при попытке чтения регистра, который используется в вычислениях происходит интерлок.
* До тех пор, пока программа не трогает используемые регистры - инструкция GTE выполняется параллельно обычным инструкциям.

Все вычисления производятся над числами с фиксированной точкой.