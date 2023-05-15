# Coding-Question-
This is a programming question preferably in python 
t = int(input())
for i in range(t):
    n = int(input())
    s = input()
    y = 0
    z = 0
    for j in range(n):
        a = int(s[j]) 
        if a==0:
            y = y + 1
        elif a==1:
            z = z + 1

   if y>=z:
       print(z)
   elif (z>y):
       print(y+1)
