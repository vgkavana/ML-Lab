#Python program to count number of characters in a string. 

a = input("Enter the string :")
f = {} 
for i in a: 
    if i in f: 
        f[i] += 1
    else: 
        f[i] = 1
print ("Count of all characters is :\n "+str(f))

Output
Enter the string :afxghbk
Count of all characters is :
 {'a': 1, 'f': 1, 'x': 1, 'g': 1, 'h': 1, 'b': 1, 'k': 1}



