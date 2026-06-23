def get number1():
    while True:
        try:
            number1 = float(input("Enter the first number: "))
            return number1
        except ValueError:
            print("Invalid input. Please enter a valid number.")
              

def get_number2():
    while True:
        try:
            number2 = float(input("Enter the second number: "))
            return number2
        except ValueError:
            print("Invalid input. Please enter a valid number.")

def add_numbers(num1, num2):
    return num1 + num2

def subtract_numbers(num1, num2):
    return num1 - num2

def multiply_numbers(num1, num2):
    return num1 * num2

def divide_numbers(num1, num2):
    try:
        return num1 / num2
    except ZeroDivisionError:
        print("Error: Division by zero is not allowed.")
        return None

def main():
    while True:
        print("\nOptions:")
        print("1. Add")
        print("2. Subtract")
        print("3. Multiply")
        print("4. Divide")
        print("5. Exit")
        
        choice = input("Enter your choice: ")
        
        if choice in ['1', '2', '3', '4']:
            num1 = get_number1()
            num2 = get_number2()
            
            if choice == '1':
                result = add_numbers(num1, num2)
                print(f"Result: {result}")
            elif choice == '2':
                result = subtract_numbers(num1, num2)
                print(f"Result: {result}")
            elif choice == '3':
                result = multiply_numbers(num1, num2)
                print(f"Result: {result}")
            elif choice == '4':
                result = divide_numbers(num1, num2)
                if result is not None:
                    print(f"Result: {result}")
        elif choice == '5':
            break
        else:
            print("Invalid choice. Please try again.")      
 main()