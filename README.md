  
# Basic-Calculator
print("Basic calculations")

# Taking user inputs
num1 = float(input("Please Enter First Number: "))
num2 = float(input("Please Enter Second Number: "))

# Choose an operation
print("Choose an Operation")
print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")

choice = input("Enter Your Choice (1/2/3/4): ")

# perform the calculation
if choice == '1':
    print("Result:", num1 + num2)
elif choice == '2':
    print("Result:", num1 - num2)
elif choice == '3':
    print("Result:", num1 * num2)
elif choice == '4':
    if num2 != 0:
        print("Result:", num1 / num2)
    else:
        print("Error: cannot divide by zero")
else:
    print("Invalid choice")

      
  
