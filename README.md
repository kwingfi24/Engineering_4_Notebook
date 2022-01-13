# Engineering_4_Notebook
Engineering 4 - Raspberry Pi, Python, Onshape
## Table of Contents
* [Python Dice Roller](#PythonDiceRoller)
* [Python Calculator](#Python_Calculator)
* [Quadratic Solver](#Quadratic_Solver)
* [Strings and loops](#Strings_and_loops)
* [MSP Challenge](#MSP_Challenge)
* [CAD Swing Arm](#CAD_Swing_Arm)
* [CAD Skateboard](#CAD_Skateboard)
* [CAD Duck](#CAD_Duck)
* [Multi-Tool](#Multi_Tool)
* [RPi GPIO Pin Intruduction](#GPIO_Pin_Introduction)
* [RPi Safe Shutdown Button](#RPI_Safe_Shutdown_Button)
* [GPIO I2C](#GPIO_I2C)
* [Headless Accelerometer](#Headless_Accelerometer)
---

## Python_Dice_Roller
### Assignment Description

The purpose of this assignment was to create a program that can automatically roll dice. The program also took user input to decide whether another dice should be rolled, or if the program should exit.

### Evidence 

##### Vanilla version:

![Screenshot 2021-09-16 9 14 33 AM](https://user-images.githubusercontent.com/60272021/133620528-a9fa2457-316c-4b7f-b66c-69d0ff2f71e8.png)

### Wiring

N/A

### Reflection
This assignment was relatively simple, but was challenging because I had not coded in Python for several months. I learned that I could import parts of toolboxes without importing the entire thing, but that changes the syntax of how I call the function later. I also learned about using a while loop to control whether a user wants to exit the program. For the spicy version, I needed to use nested loops. Python determines what is inside a loop by the indent level of each line of text, rather than brackets like some other coding styles. That means I need to be really careful with my tabs!

## Python_Calculator

### Assignment Description

This assignment takes the user's two inputs and does math with those two numbers. It gives the sum, difference, product, quotient and modulo.
### Evidence 

##### Vanilla version:

![Screenshot 2021-09-16 10 36 04 AM](https://user-images.githubusercontent.com/60272021/133631864-7301960e-5c1c-4a23-a77b-3f91d2e2e49d.png)

##### Spicy Version:

![Screenshot 2021-09-30 10 25 28 AM](https://user-images.githubusercontent.com/60272021/135474434-30f46ecc-ae61-4d9b-96e7-c98415d5f9e2.png)

### Wiring

N/A

### Reflection
This assignment was pretty simple, other than trying to find the code needed to find the modulo. The "f'" command embeds python expressions for formatting. The most difficult part was making the quotient only show 2 places after the decimal, but "round ( ,2)" worked for this.

## Quadratic_Solver
### Assignment Description

The purpose of this assignment was to create a program that can solve a quadratic using the variables/inputs given by the user. If the quadratic had no roots, the program gave the user the discriminant and said "No real roots". The user was then asked whether they wanted to run it again or exit the program. 

### Evidence 

##### Vanilla version:

![Screenshot 2021-09-21 9 17 19 AM](https://user-images.githubusercontent.com/60272021/134179410-305a5e28-3096-46b8-b26c-a06b8991aec9.png)

### Wiring

N/A

### Reflection

I kept losing my progress on this assignment, so after 20 minutes or after big changes to the code have been made I save it. Using if statements made this assignment easier since there were two posssible outcomes, either the quadratic had rots or it didn't. Using the greater than or equal to, and less than symbols is simpiler than I first thought. I also used ra again to record the users input like in previous assignments. There are easier ways to simplify the math, I used some and didnt use others.

## Strings_and_loops
### Assignment Description

The purpose of this assignment was to create a program that will split the input given by the letter.

### Evidence 

###### Vanilla version:

![Screenshot 2021-09-21 10 10 17 AM](https://user-images.githubusercontent.com/60272021/134187046-ae9c7798-d38f-43cc-9161-e7274841c1f5.png)

### Wiring

N/A

### Reflection
This was pretty simple to do, but there were new things added. I learned about strings and loops mostly through [this website](https://www.w3schools.com/python/python_for_loops.asp). It walked through different steps and how you can change it to get different outcomes. This will be helpful for the MSP Challenge coming up.

## MSP_Challenge
### Assignment Description
Make a 2 player hangman game. This program will let player 2 play the game with  word given by player two. The spicy version also adds the missed letters. I've also included codes that will be more picky onthe plyer's guesses telling them if they already tried it, didn't enter a letter, or entered multiple letters.

### Evidence 

##### Vanilla version:
![Screenshot 2021-09-30 10 01 05 AM](https://user-images.githubusercontent.com/60272021/135469982-a46ab4a2-929e-46b2-9d14-89e24effa059.png)

##### Spicy Version:

![Screenshot 2021-09-30 10 01 45 AM](https://user-images.githubusercontent.com/60272021/135470187-a8cd2345-b630-444d-9d26-009caac72faf.png)

### Wiring

N/A

### Reflection
The previous assignments helped with the basics of this assignment, but I'm not proud of how much I had to use other resources rather than my brain. Instead of searching directly for answers next time, I think I would benefit more by searching for and learning each piece. It was interesting to see how this simple game uses a pretty complicated code. Tip for the future.... break things down in parts! iIt was a lot simpiler this way and taking it bit by bit rather than biting off more than I can chew.

## CAD_Swing_Arm 

### Assignment Description

This assignment asked me to replicate a swing arm part from a set of drawings. The assignment style is similar to a portion of the Onshape Associate Certification test.

### Evidence 

##### Configuration #1

![Screenshot 2021-10-18 10 11 35 AM](https://user-images.githubusercontent.com/60272021/137748452-edd78be5-9293-4c41-979e-101bc1e99b41.png)

##### Configuration #2

![Screenshot 2021-10-18 10 15 31 AM](https://user-images.githubusercontent.com/60272021/137748826-ffa06636-07cc-4092-b044-35526aef89f6.png)

### Part Link

[Swing Arm Part](https://cvilleschools.onshape.com/documents/b20e3fd89d9f33d0597f58c1/w/6080ec1c7390420c270dd046/e/9519cc0f902e043ed5ae4153?renderMode=0&uiState=616d80202ba4eb00139a1495)


### Reflection
Creating this part from a drawing was more difficult than I expected. Combining the different drawing views with the various dimensions took several tries. Even though the part was made with simple extrudes, they were combined in relatively complex ways. Next time, I will spend more time analyzing the drawings before I actually start making the part!

## CAD_Skateboard

### Assignment Description

This assingment's purpose is to give us more practice in Onshape. This assignment showed me different things in Onshape, newer and more efficient ways to do things, and retaught me how to make an assembly after not doing it in so long.

### Evidence 

##### In the part studio:

![Screenshot 2021-10-20 6 28 48 PM](https://user-images.githubusercontent.com/60272021/138181939-c294c0a1-108f-4974-8b9e-b914005158d7.png)

![Screenshot 2021-10-20 6 44 23 PM](https://user-images.githubusercontent.com/60272021/138182825-f020b2b2-9891-4d4f-823c-b51fd63e7927.png)


##### After the assembly:

![Screenshot 2021-10-20 6 19 23 PM](https://user-images.githubusercontent.com/60272021/138180565-fabe0049-59a6-494c-bd44-0203eb372341.png)

![Screenshot 2021-10-20 6 43 04 PM](https://user-images.githubusercontent.com/60272021/138182808-b63a29d8-1666-441c-8ac1-0a9efdf5ff6c.png)


### Part Link

[Skateboard](https://cvilleschools.onshape.com/documents/831bb81580d65a7561ba4911/w/a98a3fb6435c68f3314c333e/e/afe3b851f0d2c0c4cb34e7c1?renderMode=0&uiState=6170970f97410a1ace46edfa)

### Reflection

In this assignment I found a lot of new tools, ways to do things, and practice with assemblies. After being introduced to Onshape last year, but not getting a whole bunch of practice with it, I feel a lot more confident after this assignment. I learned how to use new tool such as the replicate and offsets. I also got to do more things in the #d side of onshape like bending the board and adding holes using the hole tool. After the different part making, the assembly side of things was also very educational for me. I've always sturggled with mates and after this assignment, I feel a bit better about mates.


## CAD_Duck

### Assignment Description

In this assignment, we made a single 2x4 lego and added a bunch f configurations to it to make endless possible configurations with different sizes, types, and colors. 
### Evidence 

##### Original 2x4 Lego:

![Screenshot 2021-11-04 2 56 51 PM](https://user-images.githubusercontent.com/60272021/140407109-f1b820af-1848-4fea-8470-1cfd57cba7a6.png)

##### Configurations:

![Screenshot 2021-11-04 2 57 29 PM](https://user-images.githubusercontent.com/60272021/140407230-08c28b6a-c0cb-4620-9be7-20aa7e3c8a74.png)
 
![Screenshot 2021-11-04 2 57 44 PM](https://user-images.githubusercontent.com/60272021/140407329-f78949af-d41b-47e3-8272-1d11aaaf7262.png)
 
![Screenshot 2021-11-04 2 57 56 PM](https://user-images.githubusercontent.com/60272021/140407831-917a632e-9dee-4a49-88e3-d4b7146610c7.png)

##### After the assembly:

![Screenshot 2021-11-04 3 27 50 PM](https://user-images.githubusercontent.com/60272021/140407908-73c79a0c-79d3-40fc-949d-845ca621429d.png)

##### Drawing:

![Screenshot 2021-11-04 3 28 31 PM](https://user-images.githubusercontent.com/60272021/140407978-dec7e3f4-9d45-4dfa-b366-851f01e2e3bf.png)


![Screenshot 2021-11-04 3 28 47 PM](https://user-images.githubusercontent.com/60272021/140408072-ea8ccff3-89d6-4436-9841-26c41419ddda.png)


### Part Link

[Duck](https://cvilleschools.onshape.com/documents/f773351e58492d5fbdd4d604/w/906060e22d4cb12b5eb50a1c/e/e6f6d4b849557f79837e5227)

### Reflection

I made configurations and did a bunch of new things with them. I leanerd how to name parts, supress certain features, and color different parts through a configuration. I also learned how drawings worked (including BOMs) and variables.


## Multi_Tool

### Assignment Description

In this assignment we were given a picture to sketch into onshape, then we set it up for laser cutting. The tool we made has a wrench, straight-edge, right triangle, and measurements in both inches and centimeters. 

### Evidence

##### Part:

![Screenshot 2021-11-09 9 39 46 AM](https://user-images.githubusercontent.com/60272021/140944550-efbcc374-6b21-4049-8644-a25f3a33952b.png)

##### Drawing:

![Screenshot 2021-11-09 9 40 06 AM](https://user-images.githubusercontent.com/60272021/140944586-626e8a61-ce57-4dca-a2bc-3dbea6ffc28e.png)

##### After Cut:

Picture needed

### Part Link

[Multi-Tool](https://cvilleschools.onshape.com/documents/00cb0a55d7addc1022083cca/w/b312d2925f9426fb972086b1/e/a565bdfa7d6be8ba4132513f?renderMode=0&uiState=618a86e53ace304f78594e29)

### Reflection

This assignment showed me that I don't need step by step instruction, I know enough to do a lot of things by myself. I also learned how things need to be set up in order for things to get laser cut. You also can "Edit in context" of assmblies and add things in there, for example the wrench part of this multi-tool.


## GPIO_Pin_Introduction

### Assignmnt Description

In this assignment I was introduced to GPIO pins. After tinkering and messing around with it for a bit I wired up 2 LEDs (Red and Yellow) to blink at different times until the command CTRL + C is used. By blinking at different times I mean when red is on, yellow is off and when yellow is on, red is off.

### Evidence

https://user-images.githubusercontent.com/60272021/144076450-132a1f73-8f57-4afc-9a91-3e5d34861bd7.mp4

### Wiring

![Screenshot 2021-11-30 10 31 27 AM](https://user-images.githubusercontent.com/60272021/144077219-afcc4160-82d8-46e5-802d-5cf3abafe1d4.png)

### Reflection

It was a bit difficult to understand the different numberings, but I eventually understood the BCM system. I'd like to try and review the other systems in order to understand it all. The example codes given by Mr.Miller would not work for some reason after many attempts. I finally researched and found some commands that worked (only needed a bit more typing than perviously needed). I used [this website](https://thepihut.com/blogs/raspberry-pi-tutorials/27968772-turning-on-an-led-with-your-raspberry-pis-gpio-pins) for help. This reminded me a lot of arduino because of the way I have the outputs and pin numbers set. It was nice to see that some of the arduino I learned can still be used even in Pi. After figuring out how to get the light to turn on, it was pretty simple to get them to alternate repeatedly with just using a while loop.


## RPI_Safe_Shutdown_Button

### Assignment Description

In this assignment I copied over a script (after going through it to understand each part and learn how it was put together). This script reboots the pi when pushed and shuts the pi down when the button is pushed for 3 seconds. This is also running in the background and can be used at any time.

### Evidence

upload vid

### Wiring

![Screenshot 2021-12-02 10 16 57 AM](https://user-images.githubusercontent.com/60272021/144450104-e15ddcb4-b492-4bf8-a695-5d9b6e19768e.png)

### Reflection



## GPIO_I2C

### Assignment Description

In this assignment I used two different scripts in order to print different accelerations on a screen that updated ever half second. 

### Evidence

https://user-images.githubusercontent.com/60272021/149352193-755736e3-b96e-4cd7-a917-2ea8fe8abd01.mp4

### Wiring

![IMG-0375](https://user-images.githubusercontent.com/60272021/146018771-4f2f76d6-2e5f-4054-8c91-a09e9dbcfa5b.jpg)

### Reflection
This was a pretty simple assignment, but I would have completed it sooner if I had simply thought more about what I was being asked and how to do it. By this I mean that I originally just had numbers on the screen that were slowly stacking, creating a white box. This was a simple fix with two simple lines of code that were present in the original codes. I then had it working, but it wasn't organized because the only thing there was the numbers. Knowing this, I went back and added a heading and labels for each reading. I'd love to experiment with different fonts and sizes of text, but I'll have to come back to that later.


## Headless_Accelerometer

### Assignment Description
In this assigment we had to pick an axis (I chose to do x) and display it graphically using a dot that moves around.

### Evidence

upload vid

### Wiring 

![IMG-0375](https://user-images.githubusercontent.com/60272021/146018771-4f2f76d6-2e5f-4054-8c91-a09e9dbcfa5b.jpg)

### Reflection
I thought I had figured this assignment out in a bit under two hours; however, I noticed some strange things while I was playing around with it. I revisited my code and made a few changes. I originally was trying to show both the x and y axis, but in the final I removed the y because it was acting up. I hope to revisit this assignment, but due to time I have to leave it like this for now.
