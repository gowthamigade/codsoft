#Password generator
import random
import string

print(" PASSWORD GENERATOR ")
len_of_pswd = int(input("Enter length of password :"))
password=''
characters = string.ascii_letters + string.digits + string.punctuation
for i in range(len_of_pswd):
    print(password.join(random.choices(characters)), end="")
