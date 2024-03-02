# python
#problem based on range:--
'''n=int(input())
for i in range(1,n + 1):
       factorial = factorial*i
   print'''
   

#approch--1(without using list)
'''s,e=map(int,input().split())
s=0
for i in range(s,e+1):
  r=1
  for j in range(1,i+1):
    r=r*j
  s=s+r
print(s)'''

#approch--2(using list)
'''s,e=map(int,input().split())
a=[]
for i in range(s,e+1):
  r=1
  for j in range(1,i+1):
    r=r*j
  a.append(r)
print(sum(a))'''

#even numbers 
'''s1=0
s,e=map(int,input().split())
for i in range(s,e+1):
  if i%2==0:
    r=1
    for j in range(1,i+1):
      r=r*j
    s1=s1+r
print(s1)'''

#membership operators
'''n=int(input())
a=list(map(int,input().split()))
x=[]
for i in range(n):
  if a[i] not in x:
    x.append(a[i])
print(x)'''
# without range==
n=int(input())
a=list(map(int,input().split()))
x=[]
for i in a:
  if i not in x:
    x.append (i)
print(x)
