- 👋 Hi, I’m @Stervatnik
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
import math


def func1():
    x = float(input("Введите длину прямоугольника: "))
    y = float(input("Введите ширину прямоугольника: "))
    res = x * y
    print("Площадь равна : ", res)


def func2():
    x = float(input("Введите основание: "))
    y = float(input("Введите высоту: "))
    res = x * y / 2
    print("Площадь равна : ", res)


def func3():
    x = float(input("Введите радиус r = "))
    res = math.pi * (x ** 2)
    print("Площадь равна : ", res)


a = int(input("1 - прямоугольник, 2 - треугольник, 3 - круг: "))
if a == 1:
    func1()
if a == 2:
    func2()
if a == 3:
    func3()
<!---
Stervatnik/Stervatnik is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
