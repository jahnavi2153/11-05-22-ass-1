# 11-05-22-ass-1
Q=int(input())
while(Q>0):
    X,Y=[int(X)for X in input().split()]
    sum=0
    for num in range(X+1,Y):
        c=0
        for i in range(1,1+num):
            if(num%i==0):
                c=c+1
        if(c==2):
            sum=sum+1
    Q=Q-1
    print(sum) 
    
