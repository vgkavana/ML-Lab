#Python program to sum three given integers.if two values are equal sum will be 0. 
a=int(input("Enter the 1st number"))
b=int(input("Enter the 2nd number")) 
c=int(input("Enter the 3rd number")) 
if (a==b or a==c or b==c):
  print("The sum is 0") 
else:
  print("The sum is",a+b+c) 

Output
Enter the 1st number12 
Enter the 2nd number23 
Enter the 3rd number45 
The sum is 80

Enter the 1st number12 
Enter the 2nd number12 
Enter the 3rd number34 
The sum is 0



