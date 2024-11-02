def calculator():
    print("Welcome to the Basic Calculator!")

    while True:
        try:
            num1 = float(input("Enter the first number: "))
            num2 = float(input("Enter the second number: "))
            break
        except ValueError:
            print("Invalid input. Please enter numbers only.")

    while True:
        operation = input("Choose an operation (+, -, *, /): ")
        if operation in ['+', '-', '*', '/']:
            break
        else:
            print("Invalid operation. Please try again.")

    if operation == '+':
        result = num1 + num2
        print(f"The result is: {result}")
    elif operation == '-':
        result = num1 - num2
        print(f"The result is: {result}")
    elif operation == '*':
        result = num1 * num2
        print(f"The result is: {result}")
    elif operation == '/':
        if num2 == 0:
            print("Error: Division by zero.")
        else:
            result = num1 / num2
            print(f"The result is: {result}")

    print("Thank you for using the Basic Calculator!")

if __name__ == "__main__":
    calculator()
