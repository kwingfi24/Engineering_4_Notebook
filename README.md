# Engineering_4_Notebook
Engineering 4 - Raspberry Pi


## Hello Python
#### Description: 
In this assignment we made an automatic dice roller that would give you a random number when you hit enter and stops when you enter x or any other key.

#### Code:
```
# Automatic Dice Roller
# Written by Kaitlyn Wingfield

from random import randint #importing randint from the random program, but only importing what we need
print ("Automatic Dice Roller") #printing the opening line
input ("Press Enter to roll") #printing the opening line
print(randint(1,6)) #getting a random interger between 1 and 6 then printing it
ra = input ("Roll again?") #Making "Roll again?" into a vairable for the while loop
while ra == "": #Saying that while ra is empty, which it will be because of pressing enter, to run the program again until there is some input there
    print(randint(1,6)) 
    ra = input ("Roll again?") 
print ("Goodbye!") #Once the variable is not empty the while loop will stop and "Goodbye!" will end the program
```
#### Reflection/Lessons learned:
- Using google and people around you is helpful
- Naming variables so that you can use while loops

## Python Program 01 – Calculator (Hello Functions)
#### Description:

#### Code:
```
# Python Program 01 - Calculator (ENGR4)
#Written by Kaitlyn Wingfield
#9.14.2021

def sum(a, b): #defining sum with the variables a and b (the first and second number) 
    return (a + b) #telling the formula that should be used
def difference(a, b): #defining difference with the variables a and b (the first and second number) 
    return (a - b) #telling the formula that should be used
def product(a, b): #defining product with the variables a and b (the first and second number) 
    return (a * b) #telling the formula that should be used
def quotient(a, b): #defining quotient with the variables a and b (the first and second number) 
    return (a / b) #telling the formula that should be used
def modulo(a, b): #defining modulo with the variables a and b (the first and second number) 
    return (a % b) #telling the formula that should be used
a = int(input('Enter 1st number: ')) #making the input a variable (a)
b = int(input('Enter 2nd number: ')) #making the input a variable (b)

print(f'Sum: {sum(a, b)}') #printing the sum of a and b
print(f'Differnce: {difference(a, b)}') #printing the difference of a and b
print(f'Product: {product(a, b)}') #printing the product of a and b
print(f'Quotient: {quotient(a, b)}') #printing the quotient of a and b
print(f'Modulo: {modulo(a, b)}') #printing the modulo of a and b
```

#### Reflection/Lessons learned


