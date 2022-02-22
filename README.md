# assignment-2-22.2.22
Write a program to pattern 
program for number pattern

n=int(input('enter number:'))
for i in range(1,n+1):
    for j in range(1,i+1):
        print(j,end=" ")
    print("\n")    
for i in range(1,n+1):
    for j in range(1,n-i+1):
        print(j,end=" ")
    print("\n")   

output:
enter number:4
1
1 2
1 2 3
1 2 3 4
1 2 3 
1 2 
1
Output
Enter number:5
1
12
123
1234
12345
1234
123
12
1
