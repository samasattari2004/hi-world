import winsound
from random import randint

def creat__music():
    count = 5
    while count >0:
          winsound.Beep(randint(50, 2000),randint(100, 1000))
          count-=1

  creat__music()
