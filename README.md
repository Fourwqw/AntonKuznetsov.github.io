# Портфолио Антона Кузнецова
## Hello, world!
### Немного информации обо мне.
Что я умею:  
-C++(Basic level)  
-С#(Basic level)
-С(Basic level)  
-Pyhon(low Basic level)
-JavaScript(low level)
-PascalABC  
-Excel  
-Github pages  
### Работы по Программированию:
1. Вывод таблицы истинности для не A   

```Python  
"""
		Кузнецов Антон Денисович 
		ИВТ 1.1, 2 курс
		Задание: Вывод таблицы истинности для не A  
"""
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

2. Вычисление площади треугольника по формуле Герона

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
3.

### Веб:
3 семестр:
1. Completed!
2. DTD
[Тута](https://github.com/Fourwqw/AntonKuznetsov.github.io/tree/master/part2)
3. LAB
[Тута](https://github.com/Fourwqw/AntonKuznetsov.github.io/tree/master/part2)
4. Введение
[Тута](https://kodaktor.ru/task_18c81)
5. функции 
"""
const concat = require('goss_concat');
function rgb(r = 255, g = 255, b = 255) {
  return concat('rgb(', r, ',', g, ',', b, ')');
}
console.log(rgb(14, 188)); 
document.querySelector('button')
.addEventListener(
  'click',
   e => {
     const result = rgb(255,10);
     document.body.style.backgroundColor = result;
     e.target.textContent = result; 
   }
);
"""
6. Зависимость
[Тута](https://kodaktor.ru/task_func_8589b)
8. Счётчик
[Тута](https://kodaktor.ru/2c4cefb_bbbd4)
9. jQuery
[Тута](https://kodaktor.ru/zzzzzzz_376d7)
10. IIFE
[Тута](https://kodaktor.ru/16102018_8cd7e)
11. LAB
[Тута](https://kodaktor.ru/08fd736_140f4)

12.Async/fetch 
[Тута](https://kodaktor.ru/13112018_04372)
### Фото моего кота
![MyCat](руби.jpg "Mimimi")
#### EditWorld
##### AntonKuznetsov.github.io
