# BMI
# cook your dish here
t=int(input())
while t:
    m,h=map(int,input().split())
    a=(m/(h**2))
    if(a<=18):
        print("1")
    elif(19<=a<=24):
        print("2")
    elif(25<=a<=29):
        print("3")
    else:
        print("4")
    t-=1
