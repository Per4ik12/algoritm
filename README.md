number = float (input("Введите пятизначное число: "))
tens = number // 10 % 10
ones = number % 10
hundreds = number // 100 % 10
thousands = number // 1000 % 10
ten_thousands = number // 10000
result = (tens ** ones) * hundreds / (ten_thousands - thousands)
print("Результат:", result)
