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
#### Reflection/Things learned:
- Using google and people around you is helpful
- Naming variables so that you can use while loops
