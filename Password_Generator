import random
import string

def password_generator(size=12, chars=string.ascii_uppercase + string.ascii_lowercase + string.digits + string.punctuation):
    return ''.join(random.choice(chars) for _ in range(length))
    return password

try:
    num_password = int(input("Enter how many passwords you want to generate:"))
    length = int(input("Enter password length:"))
    if length <8:
        print("password length should be at least 8 characters")
    else:
        print("Generated password is:", password_generator(length))
        for i in range(num_password):
            print(f"{i+1}: {password_generator(length)}")
except ValueError:
    print("Invalid input! Please enter a valid number.")
