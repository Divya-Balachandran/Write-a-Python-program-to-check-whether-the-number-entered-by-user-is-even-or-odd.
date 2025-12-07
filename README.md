num = int(input("Enter any number: "))
flag = num%2
if flag == 0:
   print(num, "is an even number")
elif flag == 1:
   print(num, "is an odd number")
else:
   print("Error, Invalid input")

OUTPUT:

Enter any number: 34
34 is an even number

Enter any number: 19
19 is an odd number
