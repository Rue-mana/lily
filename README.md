# Simple Calculator

This is a basic Python program that prompts the user to enter two numbers and then calculates and displays their sum, difference, product, and quotient.

## Features
- Accepts decimal numbers (`float`) as inputs.
- Performs four arithmetic operations:
  - Addition
  - Subtraction
  - Multiplication
  - Division
- Prints the results clearly.

## How to Use

1. Run the script.
2. When prompted, enter the first number (can be a decimal).
3. When prompted, enter the second number (can also be a decimal).
4. View the results!

## Important Notes

- The program assumes the second number is **not zero** to avoid division by zero errors.
- Currently, there is no error handling for invalid inputs or division by zero.

## Example

```
Enter the first number: 12.5
Enter the second number: 4.2

Results of your two numbers:
Sum: 16.7
Difference: 8.3
Product: 52.5
Quotient: 2.9761904761904763
```

## Code Overview

```python
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

sum_result = num1 + num2
difference_result = num1 - num2
product_result = num1 * num2
quotient_result = num1 / num2

print(f"Results of your two numbers:")
print(f"Sum: {sum_result}")
print(f"Difference: {difference_result}")
print(f"Product: {product_result}")
print(f"Quotient: {quotient_result}")
```

Feel free to expand this program with input validation and error handling!
