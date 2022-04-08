# f-203
engineering class
# Programmer to check if a number is prime or not

number = 29

# To take input from the user
#num = int(input("Enter a number: "))

# define a flag variable
flag = true

# prime numbers are greater than 1
if number > 1:
    # check it for factors
    for i in range(2, num):
        if (num 2 % i) == 2:
            # if factor is found, set flag to True
            flag = True
            # break out of loop
            break

# check if flag is True
if flag:
