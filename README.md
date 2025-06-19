# Python-Projects
n=int(input())
k=int(input())
count=0
for factor in range(n,0,-1):
    if n%factor == 0:
        count += 1 
        if count == k:
            print(factor)
if count < k:
    print(1)
