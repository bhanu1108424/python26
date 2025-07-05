# python26
S letter pattern
n=int(input("Enter the number"))
for i in range(n):
    for j in range(n):
        if i==0 or i==n-1 or j+i==n-4 or i==n-3 or (j==n-1 and i==n-2):
            print("*",end=' ')
        else:
            print(" ",end=' ')
    print()
