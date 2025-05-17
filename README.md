# project-1-for-microIT
calculator project
<br>
Python code for the calculator:
<br>
def calculate(a, b, op):
<br>
    try:
    <br>
        a = float(a)
        <br>
        b = float(b)
        <br>
        if op == '+':
        <br>
            return a + b
            <br>
        elif op == '-':
        <br>
            return a - b
            <br>
        elif op == '*':
        <br>
            return a * b
            <br>
        elif op == '/':
        <br>
            if b == 0:
            <br>
                return "Error: Division by zero"
                <br>
            else:
            <br>
                return a / b
                <br>
        else:
        <br>
            return "Invalid operator"
            <br>
    except:
    <br>
        return "Invalid input"
        <br>

a = input("Enter first number: ")
<br>
b = input("Enter second number: ")
<br>
op = input("Enter operation (+, -, *, /): ")
<br>

result = calculate(a, b, op)
<br>
print("Result:", result)
