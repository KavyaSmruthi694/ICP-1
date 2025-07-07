# ICP-1

# Part a: String manipulation
input_string = list(input("Enter the string \"Python\": "))
# Delete characters (example: deleting characters at index 1 and 3)
if len(input_string) >= 4:
  del input_string[3]
  del input_string[1]
# Reverse the resultant string
input_string.reverse()
# Print the reversed string
print("".join(input_string))
# Part b: Arithmetic operations
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
# Perform arithmetic operations
print("Addition:", num1 + num2)
print("Subtraction:", num1 - num2)
print("Multiplication:", num1 * num2)
if num2 != 0:
  print("Division:", num1 / num2)
else:
  print("Division by zero is not allowed.")
