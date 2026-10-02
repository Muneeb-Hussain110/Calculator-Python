# Calculator-Python
def calc(a, b, op):
    if op == '+':
        return a + b
    elif op == '-':
        return a - b
    elif op == '*':
        return a * b
    elif op == '/':
        return a / b

x = float(input("Enter first number: "))
y = float(input("Enter second number: "))
o = input("Enter operator (+, -, *, /): ")

print("Result =", calc(x, y, o))
