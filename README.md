# CODEchefstarters23-JAN26
t=int(input())
for i in range(0,t):
    a=int(input())
    for i in range(1,3*a):
        for j in range(1,3*a):
            if j!=i:
             for k in range(1,3*a):
                if k!=j and k!=i:
                 if (i+j+k)//3==a:
                    break
             break
        break
    
    print(i,end=' ')
    print(j,end=' ')
    print(k,end=' ')
    print()
