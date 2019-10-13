# Портфолио Антона Кузнецова
## Hello, world!
### Немного информации обо мне.
Что я умею:  
-C++(Basic level)  
-С(Basic level)  
-PascalABC  
-Excel  
-Github pages  
### Работы по Программированию:
1. Вычисление площади треугольника по формуле Герона
```Python
"""
		Кузнецов Антон Денисович 
		ИВТ 1.1, 2 курс
		Задание: вычисление площади треугольника по формуле Герона
"""
import math

def geron_sq(a,b,c):
	"""
		Функция вычисляет площадь треугольника по трем сторонам.


	"""
	p = int((a + b + c) / 2)
	res = p * math.sqrt((p - a) * (p - b) * (p -c))
	return res

def main():
	"""
		Функция всех функций
		
	"""
	a = int(input("Введите сторону a:"))
	b = int(input("Введите сторону b:"))
	c = int(input("Введите сторону c:"))
	print(geron_sq(a, b, c))


main()
input()
```
2. Вывод таблицы истинности для не A
```Python
header = "- A -- not A -"
tmpLen =  len(" not A ")
dot = "-"
A = [1, 0]
print(dot * len(header) +"\n" + header + 
     "\n" + dot * len(header))
print(dot + " " + str(A[0]) + " " + dot*2 +
	 tmpLen // 2 * " " + str(int(not A[0])) + tmpLen // 2 * " " + dot +
	 "\n" + dot * len(header) +"\n" +
	 dot + " " + str(A[1]) + " " + dot*2 +
	 tmpLen // 2 * " " + str(int(not A[1])) + tmpLen // 2 * " " + dot 
	 + "\n" + dot * len(header) +"\n")
input()
```
3.
### Работы по веб-дизайну
1.
### Фото моего кота
![MyCat](руби.jpg "Mimimi")
#### EditWorld
##### AntonKuznetsov.github.io
