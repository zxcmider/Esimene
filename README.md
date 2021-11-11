#num = int(input( "Введите число"))
#sum=0

#for i in range(1, num+1): 
#    sum+= i
#    print(sum)


#t=0
#q=0
#while t<15:
#   t+=1
#   a=float(input("Sisesta arv"))
#   if a==round(a): q+=1
#print("Good",q)


#A=10   #2
#s=0
#for arv in range(1,A+1):
#   s+=arv
#print("Summa: ",s)

#from random import *  #3
#korrutis=1
#for i in range(8):
#   B=randint(-100,100)
#   print(B)
#   if B>0: korrutis*=B
#print("Korrutis on ",korrutis)

#4
#b=0
#for b in range(10,20):
#   b^=2
#print("Kvadrat",b)

#5
#from random import *
#N=int(input("Mitu: "))
#p=n=o=0
#while N>0:
#    N-=1
#    B=randint(-100,100)
#    print(B)
#    if B>0:
#       p+=1
#    elif B<0:
#         n+=1
#    else:
#         o+=1
#print("Positiivne: ",p)
#print("Neg",n)
#print("Nul:",o)

#print("Дорбо пожаловать в магазин")
#print("Купи слона!")
#otv1=input()

#otv1=input("Все говорят купи слона"+(str(otv1)+"А ты купи слона"))
#if otv1=="Хорошо":
#   print("Держи слон твой")
#elif otv1=="Нет":
#   print("R:КУПИ СЛОНА ВСЕ ХОТЯТ СЛОНА")
#   print("R:КУПИ СЛОНА")
#otv2=input()
#if otv2=="Хорошо":
#   print("R:Слон твой - поздравляю вы потратили все деньги на слона!")
#elif otv2=="Нет":
#   print("R:КУПИ СЛОНА")
#   print("Уйти с магазина 1-да 2-нет")
#otv3=input()
#if otv3=="1":
#   print("Вы вышли с магазина")
#elif otv3=="2":
#   print("R:КУПИ СЛОНА - вы застряли в этом магазине навечно поздравляю!")
#print("Купи слона!")
#otv=input()
#while(True): otv=input("Все говорят " + (str(otv)+". А ты купи слона!\n"))

loom=input("Купи слона")
while loom.title()!="Слон":
   loom=input("Все говорят"+loom+"!А ты купи!!!")
print("Слон твой!!!")
