# KRISHNAMURTHY-S-NUMBER
num=int(input("enter a number"))
temp=num
sum=0
while(temp!=0)
r=temp%10
f=1
i=1
while(i<=r):
f=f*i
i+=1
sum=sum+f
temp=temp//10
print(sum)


