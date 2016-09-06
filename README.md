# dpSplines
Discrete periodic splines with vector coefficient

Реализует алгоритм вычисления дискретного N-периодического сплайна с векторными коэфициентами.

Теория: 

http://www.math.spbu.ru/ru/mmeh/AspDok/pub/2010/Chashnikov.pdf

http://dha.spb.ru/PDF/discreteSplines.pdf

Как использовать: 

```C#
var vectors = new Vector2[N];
...
var spline = DpSpline.Calculate(vectors, 2, 10, true);
```
		
Результат: 

![Иллюстрация к проекту](https://raw.githubusercontent.com/denxc/dpSplines/master/DpSplines/SplinesTest/image.jpg)