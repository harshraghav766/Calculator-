a=int(input("enter first number : ")) #input function is used to take 1st input from user
b=(input("enter second number : ")) #input arithmatic sign  is used to take input from user
c=int(input("enter second number : ")) #input function is used to take 2nd input from user
if b=='+': #for addition
    print(a+c)
elif b=='-': #for subtraction
    print(a-c) 
elif b=='*': #for multiplication
    print(a*c)
elif b=='/': #for division
    print(a/c)
else:
    print("invalid operator") #if user enter invalid operator then this will be printed
 
