# Python-Learning
# Python practice codes and homeworks
# Udemy-session 2 homework

import math
import numpy as np
from numpy.random import randn
n=int(input('enter the range value: '))
print ('the values of N  are: ')
counter=0
for i in randn(n):
  print (i)
  if (i>-1 and i<1):
    counter=counter+1
print (counter)
