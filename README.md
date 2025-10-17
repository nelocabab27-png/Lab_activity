# Lab_activity
#Task_1
a = 15
b = 4

addition = a + b
subtraction = a - b
multiplication = a * b
floating_division = a / b
integer_division = a // b
modulus = a % b
exponentiation = a ** b

print("Addition:", addition)
print("Subtraction:", subtraction)
print("Multiplication:", multiplication)
print("Floating-Point Division:", floating_division)
print("Integer Division:", integer_division)
print("Modulus:", modulus)
print("Exponentiation:", exponentiation)

#Task_2
result1 = 5 + 3 * 2 ** 2
result2 = (5 + 3) * 2 ** 2
result3 = 10 % 3 + 5 * 2

print("Result 1:", result1)
print("Result 2:", result2)
print("Result 3:", result3)

#Task_3
inches = int(input("Enter the number of inches: "))

feet = inches // 12
remaining_inches = inches % 12

print(f"{inches} inches is equal to {feet} feet and {remaining_inches} inches.")

#Task_4
base_price = 12
age = int(input("Enter your age: "))
is_student = input(

#Task_5
correct_username = "alice"
correct_password = "wonderland"
correct_2fa_code = "123456"
is_2fa_enabled = True

input_username = input("Enter username: ")
input_password = input("Enter password: ")

# Prompt for 2FA code only if 2FA is enabled
if is_2fa_enabled:
    input_2fa_code = input("Enter 2FA code: ")
else:
    input_2fa_code = None

# Check login conditions
if (input_username == correct_username and
    input_password == correct_password and
    (not is_2fa_enabled or input_2fa_code == correct_2fa_code)):
    print("Login successful!")
else:
    print("Login failed!")
    
