# ProblemCategory
# cook your dish here
t=int(input())
while t:
    x=int(input())
    if(1<=x<100):
        print("Easy")
    elif(100<=x<200):
        print("Medium")
    elif(200<=x<=300):
        print("Hard")
    else:
        print("none")
    t-=1
