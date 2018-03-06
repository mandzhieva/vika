# vika
##1 
import math
a=int(input("a="))
b=int(input("b="))
c=int(input("c="))
p=(a+b+c)/2
print(math.sqrt(p*(p-a)*(p-b)*(p-c)))


##2
 
import math
a=int(input("введи число:"))
k=range(a)
for i in range(2,a):

  for j in  range(a):

    if ((j % i == 0) & (j != i)):

      k.remove(num)

print(k)  


##3

a=int(input("число 1:"))
b=int(input("число 2:"))
spisok = []

for i in range(a,b):
  if i % 5 == 0: 
    spisok.append(i)
print(spisok)

##4
import math
a=int(input("Введите число:"))
b=int(input("Введите число:"))
c=int(input("Введите число:"))
if b**2-4*a*c<0:
  print("Решения нет")
elif b**2 - 4 * a * c > 0:
  x1 = (-b - math.sqrt(b**2 - 4 * a * c)) / (2 * a)
  x2 = (-b + math.sqrt(b**2 - 4 * a * c)) / (2 * a)
  print(x1, x2,"Решение есть")
  
 ##5
 import numpy as np
import math
Debtss = {"Вика":10, "Света":15, "Даша":80, "Аня":4,"Лиза":90,"Женя":78,"Настя":98,"Катя":100,"Екатерина":800,"Лена":80}

mean=np.mean(list(Debtss.values())
sum1 = np.sum(Debtss.values())
Var = np.var(list(Debtss.values()))
