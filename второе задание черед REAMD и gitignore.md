arr = [1, 2, 3, 4, 5, 10, 19, 25, 88, 100]

summa = 0

for number in arr:
    if number % 5 == 0:
        summa += number
    else:
        print(f"{number} не делится на 5, пропускаем")

print(f"Сумма чисел, делящихся на 5: {summa}")
