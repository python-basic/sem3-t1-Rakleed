# Инвариативная самостоятельная работа № 1

### [1.1. Создание простейшего сценария по выводу текста на экран.](https://repl.it/@Rakleed/programming-indepworkinvar1-1)
```python
"""
    Автор: Моисеенко Павел, группа № 1, подгруппа № 2.

    ИСР 1.1. Задание: создать простейший стенарий по выводу текста на экран.
    
"""

print("Hello, World!")
```
### [1.2. Разработка скрипта, вычисляющего сумму первых n-членов арифметической прогрессии.](https://repl.it/@Rakleed/programming-indepworkinvar1-2)

```python
"""
    Автор: Моисеенко Павел, группа № 1, подгруппа № 2

    ИСР 1.2. Задание: разработать скрипт, вычисляющий сумму первых 
    n-членов арифметической прогрессии (использовать функции, условные операторы).

    Прогрессия от 1 с шагом 1.
"""

def summa(s):
    return sum(list(range(s+1)))

def main():
    numbers = int(input())
    if numbers >= 2:
        print("Сумма = " + str(summa(numbers)) + ".")
    else:
        print("Введите целое число больше 1.")
        main()

print("Программа считает сумму n-членов арифметической прогрессии.\n"
     "Скольких членов вы хотите узнать сумму?")

main()
```
