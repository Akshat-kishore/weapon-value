# weapon-value
for z in range(int(input())):
    count=0
    n=int(input())
    r=0
    for i in range(n):
        r=r^(int(input(),2))
    while r>0:
        if r%2==1:
            count+=1
        r=r//2
    print(count)
    
    
    #output: 4
