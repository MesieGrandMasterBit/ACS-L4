Лабораторная работа №4. Оптимизация доступа к памяти. 
=======================================
### Выполнил: Высотин Кирилл Евгеньевич

#### Предельные размеры матрицы:
Возьмём 80% от имеющихся 8 Gb RAM = 6,4 Gb RAM свободных для умножения матриц. 
1 элемент типа double занимает 8 байт, поэтому делим 6,4 Gb на 8 байт = 0,8 млрд элементов, которые нам необходимо выделить память под 3 матрицы. 
Делим 0,8 на 3 = приблизительно 266 млн элементов для 1 матрицы. 
Этого хватит для умножения квадратных матриц размера приблизительно 16.300 х 16.300
