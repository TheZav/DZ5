# DZ5
#Не впевнений чи правильно зрозумів завдання, але я щось зробив
#Прошу сказати мені якщо неправильно
class Ice1:
    def __init__(self,one):
      self.o = one
      print("You have picked a",self.o,"ice cream. How original.")
class Ice2:
    def __init__(self,one,two):
      self.o = one
      self.t = two
      print("You have picked a",self.o,"and a",self.t,"ice cream. That's a decent pickT.")
class Ice3:
    def __init__(self,one,two,three):
      self.o = one
      self.t = two
      self.th = three
      print("You have picked a",self.o,", a",self.t,"and a",self.th,"ice cream. Don't you think that's too much?")
a = int(input("How many different ice creams do you want?(3 max)   "))
if a == 1:
  i = input("What kind of ice cream do you want?   ")
  Ice1(i)
if a == 2:
  i = input("What kind of ice cream do you want?   ")
  i1 = input("What other kind of ice cream do you want?   ")
  Ice2(i,i1)
if a == 3:
  i = input("What kind of ice cream do you want?   ")
  i1 = input("What other kind of ice cream do you want?   ")
  i2 = input("What other kind of ice cream do you want?   ")
  Ice3(i,i1,l2)
