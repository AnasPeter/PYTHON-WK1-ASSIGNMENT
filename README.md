# PYTHON-WK1-ASSIGNMENT
Python week one assignment

# Get user input
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Enter the operation (+, -, *, /): ")

# Perform the operation based on user's input
if operation == "+":
    result = num1 + num2
elif operation == "-":
    result = num1 - num2
elif operation == "*":
    result = num1 * num2
elif operation == "/":
    if num2 != 0:
        result = num1 / num2
    else:
        result = "Error! Division by zero."
else:
    result = "Invalid operation"

# Display the result
print(f"The result of {num1} {operation} {num2} is: {result}")
Example:
If the user inputs:
Enter the first number: 10
Enter the second number: 5
Enter the operation (+, -, *, /): +
The output will be:
The result of 10.0 + 5.0 is: 15.0
