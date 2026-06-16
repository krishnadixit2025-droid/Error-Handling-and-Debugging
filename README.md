# Error-Handling-and-Debugging
# Program to safely divide two numbers
try:
    numerator = 100
    denominator = int(input("Enter divisor: "))
    result = numerator / denominator
except ZeroDivisionError:
    print("Error: You cannot divide a number by zero!")
except ValueError:
    print("Error: Please provide a valid integer.")
else:
    print(f"Division successful! Result: {result}")
