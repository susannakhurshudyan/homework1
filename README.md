# Найдите сумму цифр трехзначного числа
print ("Введите трехзначное число:")
a = int (input())
print(int(a // 100 + (a % 100) // 10) + (a % 10))

# Петя, Катя и Сережа делают из бумаги журавликов. Вместе
# они сделали S журавликов. Сколько журавликов сделал каждый
# ребенок, если известно, что Петя и Сережа сделали одинаковое
# количество журавликов, а Катя сделала в два раза больше журавликов,
# чем Петя и Сережа вместе?

print ("Всего журавликов:")
k = int (input ())
print ("Петя:" , int((1/6)*k))
print ("Катя:" , int((4/6)*k))
print ("Сережа:" , int((1/6)*k))

# Вы пользуетесь общественным транспортом? Вероятно, вы
# расплачивались за проезд и получали билет с номером. Счастливым
# билетом называют такой билет с шестизначным номером, где сумма
# первых трех цифр равна сумме последних трех. Т.е. билет с номером
# 385916 – счастливый, т.к. 3+8+5=9+1+6. Вам требуется написать
# программу, которая проверяет счастливость билета.

print("Введите шестизначное число:")
b = int (input())
if int((b // 100000 + (b % 100000) // 10000 + (b % 10000) // 1000 == (b % 1000) // 100 + (b % 100) // 10 + (b % 10))):
    print("YES")
else: print ("NO")

# Требуется определить, можно ли от шоколадки размером n
# × m долек отломить k долек, если разрешается сделать один разлом по
# прямой между дольками (то есть разломить шоколадку на два
# прямоугольника)

print("Введите значение n:")
n = int(input())
print("Введите значение m:")
m = int(input())
print("Введите значение k:")
k = int(input())
i = 0
j = 0
while i < m or j < n:
    i+=1
    j+=1
    if k == n * i:
        print ("YES")
    elif k == m * j:
        print ("YES")
else: 
        print ("NO")
  
    
