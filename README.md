# ass-2-8-5-22
Assignment-2
from math import sqrt
def square(s):
   root = int(sqrt(s))
   return (root*root) == s

n=int(input())
l=[]
d={}
for i in range(1,1000):
    x=int(input())
    l.append(x)
for i in l:
    if square(i):
        d[i]='yes'
    else:
        d[i]='no'
print(d)
