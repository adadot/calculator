# calculator
num1 = int(input("Enter Number 1:"))
oper = input("Enter the Operator")
num2 = int(input("Enter Number 2:"))

if oper == "*":
    ans = num1 * num2

elif oper == "+":
    ans = num1 + num2

elif oper == "/":
    ans = num1 / num2

elif oper == "-":
    ans = num1 - num2

print(num1, oper, num2, "=", ans)
