# GitPythonPractice
## Assignment_1
# Perform Basic Mathematical Operations
num1=int(input("enter first number:" ))
num2=int(input("enter second number:" ))
print(f"Addition = {num1+num2} " )
if num2 > num1 :
    print(f"Substraction = {num2-num1}")
else :
    print(f"Substraction = {num1-num2}")
if num2 !=0 & num1 !=0:
    print(f"Multiplication = {num2*num1}")
else :
    print(f"Multiplication is 0")

if num2 !=0 & num2 >= num1:
    print(f"Division = {num1/num2}")
elif num2 ==0 : 
    print(f"Division is not valid")
else:
    print(f"Division = {num1 / num2}")
