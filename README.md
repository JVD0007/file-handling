# file-handling
fp1=open(“G:\\Files\\mark.txt","r")
n=int(fp1.readline())
print("Total students:",n)
for i in range(n):
print("Student #",i+1,":",end="")
allgrades=(fp1.readline().split())
print(allgrades)
sum=0
for j in range(len(allgrades)):
sum=sum+int(allgrades[j])
per=float((sum/500)*100)
print('Total=',sum,"\nPercentage=",per)
print("\n")
