# NET.S.2017.Zmitrovich.02

Дан массив целых чисел. Найти в массиве и вернуть такой индекс n, для которого сумма элементов слева от него равно сумме элементов справа. Если такого индекса нет вернуть null   или -1.
Например:
-	Для массива {1,2,3,4,3,2,1} функция вернет индекс 3, поскольку на 3-й
 позиции массива, суммы слева от индекса ({1,2,3}) и справа от индекса ({3,2, 1})
  равны 6.
-	Для массива {1,100,50, -51,1,1} функция вернет индекс 1, поскольку на 1-й 
позиции массива, суммы слева от индекса ({1}) и справа от индекса ({50, -51,1,1 }) 
равны 1.

Входные данные: Целочисленный массив длины 0 <length <1000. Числа в массиве могут быть любым целыми положительными или отрицательными.

Выходные данные: Наименьший индекс, для которого сторона слева равна стороне справа. Если такого индекса не существует вернуть -1(null).
 
Разработать unit-тесты для тестирования метода (здесь и далее желательно использовать для тестирования NUnit Framework).

