# Create-a-faulty-calculator
#We need to create a faulty calculator.all the result will be correct accept for these views.(a) 45*3=555,(b) 56+9=7 (c)56/6=4
print("This is a faulty calculator to perform calclutions according to your requirements")
num =int(input("Enter first number:\n"))
num1 =int(input("Enter second number:\n"))
print('So what you want?'+',-,/,*')
num2=input("Give me the symbol you want :\n")
if num==45 and num1==3 and num2=='*' :
    print("555")
elif num==56 and num1==9 and num2=='+':
    print("7")
elif num==56 and num1==6 and num2=='/':
    print("4")
