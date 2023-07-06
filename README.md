# DavendraAndWaterSports
# cook your dish here
t=int(input())
while t:
    z,y,a,b,c=map(int,input().split())
    if((y+a+b+c)<=z):
        print("yes")
    else:
        print("no")
    t-=1
