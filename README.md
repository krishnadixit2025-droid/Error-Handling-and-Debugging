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

OUTPUT : <img width="940" height="637" alt="Screenshot 2026-06-16 152605" src="https://github.com/user-attachments/assets/0b32cc3a-0cbe-44b0-bac2-795800839814" />
