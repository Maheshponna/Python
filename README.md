# Python
s=int(input())
if s in range(0,100):
    if s>0:
        print(s,"is a positive")
    elif s<0:
        print(s,"is a Neigitive")
    if s%2==0:
        print(s,"is an even")
    elif s%2!=0:
        print(s,"is an odd")
else:
    print("ntng")
n=int(input())
for i in range(2,n//2):
    if n%i==0:
        print(n,"is not a prime number")
    else:
        print("is composite")
