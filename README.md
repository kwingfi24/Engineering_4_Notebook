# Engineering_4_Notebook
Engineering 4 - Raspberry Pi
## Table of Contents
* [Python_Dice_Roller](#PythonDiceRoller)
* [Python_Calculator](#Python_Calculator)
---

## Python_Dice_Roller
### Assignment Description

The purpose of this assignment was to create a program that can automatically roll dice. The program also took user input to decide whether another dice should be rolled, or if the program should exit. The spicy version added complexity by asking the user to specify the number of sides on the dice and the number of dice to be rolled at a time. The user was then asked whether they wanted to roll again with the same settings, change the settings, or exit the program. 

### Evidence 

Vanilla version:

![Screenshot 2021-09-16 9 14 33 AM](https://user-images.githubusercontent.com/60272021/133620528-a9fa2457-316c-4b7f-b66c-69d0ff2f71e8.png)


### Code
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
### Wiring

N/A

### Reflection
This assignment was relatively simple, but was challenging because I had not coded in Python for several months. I learned that I could import parts of toolboxes without importing the entire thing, but that changes the syntax of how I call the function later. I also learned about using a while loop to control whether a user wants to exit the program. For the spicy version, I needed to use nested loops. Python determines what is inside a loop by the indent level of each line of text, rather than brackets like some other coding styles. That means I need to be really careful with my tabs!

## Python_Calculator

### Assignment Description

This assignment takes the user's two inputs and does math with those two numbers. It gives the sum, difference, product, quotient and modulo.
### Evidence 

Vanilla version:

![Screenshot 2021-09-16 9 39 53 AM](https://user-images.githubusercontent.com/60272021/133622600-0a2f2e3d-2e95-495c-bc04-6395f5926dba.png)


### Code
```
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
print ("Calculator Program") #printing the opening line
a = int(input('Enter 1st number: ')) #making the input a variable (a)
b = int(input('Enter 2nd number: ')) #making the input a variable (b)

print(f'Sum: {sum(a, b)}') #printing the sum of a and b
print(f'Differnce: {difference(a, b)}') #printing the difference of a and b
print(f'Product: {product(a, b)}') #printing the product of a and b
print(f'Quotient: {(round (quotient(a, b), 2))}') #printing the quotient of a and b (only 2 decimals)
print(f'Modulo: {modulo(a, b)}') #printing the modulo of a and b
```

### Wiring

N/A

### Reflection
This assignment was pretty simple, other than trying to find the code needed to find the modulo. The "f'" command embeds python expressions for formatting. The most difficult part was making the quotient only show 2 places after the decimal, but "round ( ,2)" worked for this.



