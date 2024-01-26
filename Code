import random
letters=['A','B','C','D','E','F','G','H','I','J','K','L','M','N','O','P','Q','R','S','T','U','V','W','X','Y','Z']
lowers=['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']
numbers=['0','1','2','3','4','5','6','7','8','9']
symbols=['!','@','#','$','%','^','&','*','(',')']
print("Hy! Welcome to the Password Generator")
password=[]
user_choice=int(input("What is the length of password you want?"))
if(user_choice!=0):
    print(f"Password length left",user_choice)
    letter_digits=int(input("How many upper_case letters do you want?"))
    for i in range(1, letter_digits + 1):
        password.append(random.choice(letters))
    user_choice-=letter_digits
if(user_choice!=0):
    print(f"Password length left", user_choice)
    lower_digits=int(input("How many lower_case letters do you want?"))
    for i in range(1, lower_digits + 1):
        password.append(random.choice(lowers))
    user_choice-=lower_digits
if(user_choice!=0):
    print(f"Password length left", user_choice)
    number_digits=int(input("How many number of digits do you want?"))
    for i in range(1, number_digits + 1):
        password.append(random.choice(numbers))
    user_choice -= number_digits
if (user_choice != 0):
    print(f"Password length left", user_choice)
    symbol_digits=int(input("How many symbols do you want?"))
    for i in range(1, symbol_digits + 1):
        password.append(random.choice(symbols))
random.shuffle(password)
your_password=""
for char in password:
    your_password+=char
print("Your Password is ",your_password)
