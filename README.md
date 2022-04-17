# 13.8.19
kol_vo=int(input("укажите количество билетов"))
print("сколько лет каждому посетителю?")
cost=0
For i in range(kol_vo):
age=int(input("возраст каждого посетителя равен ")
If age <18:
  cost=0
Elif 18<=age<25:
  cost=cost+990
else:
  cost=cost+1399
if kol_vo>3:
  skidka=0.9
print ("цена равна - ",cost*skidka)
