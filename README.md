# Astrologers-star
#print stars in a specific pattern
# Astrologers Star
print("Enter the value of n:",end=" ")
n=int(input())
m=n
print("Enter the value of boolean:",end=" ")
bool=int(input())
if bool==1:
    print("True")
    while(n!=0):
        n=n-1
        i=n
        while(i>0):
            print("*",end="")
            i=i-1
        print("*")
elif bool==0:
    print("False")
    while(n!=0):
        n=n-1
        i=n
        while(i<m-1 and i>=0):
            print("*",end="")
            i=i+1
        print("*")
