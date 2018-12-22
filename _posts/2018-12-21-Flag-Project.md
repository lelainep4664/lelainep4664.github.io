---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## United States Flag by Lelaine Perez

## Describe your program
The country I chose to design for was the Untited States because I thought that I would be able to program the Flag in time however, I didn't exactly finish the flag program so I think that I will overall get a practioner at the most however, the program doesnt exactly run the way I wanted it to since the flag does not scale correctly down to a specific size. so far it only scales to 100 or 200. 


## Current output

* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.
One thing I wish I did during this project was ask for more help from my teacher instead of solely trying to figure out the problem by myself. I asked one of my peers who had the same Flag as I and asked them how they went about creating the stripes without them giving me the exact code. After listening to their process, it was more easier to understand. Another thing that brought me the exact colors of the flag was asking how to use the image-structs library in Pyret in order for me to create colors of my own using the exact RGB colors of the United states flag. The biggest strategy I used when creating the flag was just defining all of the proportions and then naming them in order to make it easier to use them later. 


## Explain your code.
```
size = 200
width = size * 1.9
height = size * 1
SH =  height / 13
BW = size * 0.5385
BL = size * 0.76
UH = height * (7 / 13) 
UW = width * 	0.76
```

In the first part of the argument in the code above, I used a simple code that my teacher showed us in class where we used the size variable in order to create a function that will change the size of the program, As I said the code is somewhat functional how ever, it only works to a certain extent. What the code is supposed to do is take all the variables with the value "size" and update the size of the image by what ever number I change the size value too. The reason why I think this isn't completely working is that there are other parts of the program that contridicts the size function and is using numbers that will place an image in a specific place. The "width" and the "height" are names that I assigned to the program and take the "size" function and multiply the number assigned to the size values and multiply the variable by the exact proportions of the American Flag in order to scale the image of the flag to a specific size and still keep the correct proportions of the flag. The next few parts of the code define the exact proportions of the smaller parts of the flag. "SH" is the code that takes in the proportions of the height of the stripes in the flag and divides the hieght variable by 13 in order to fit all 13 stripes on the flag. "BW" is the width of the blue union of the flag and I used an operator that will multiply the size of the Blue rectangle and use the correct proportions to give the program what it needs in order to produce the simple shapes later in the program. "BL" is the code that defines the length of the blue union of the flag and this also updates the union size in order for the program to change with the variables. The "UH" and the "UW" are somewhat "strange" in this code this also defines the Union height and width however both "BW", "BL" and "UH", "UW" work on different parts of the code in order to do different things. "BW", "BL" work on the part of the code that defines the shapes and images in the code where as "UH", "UW" work in the place image part of the code later on. 

* * *
The code below shows the entirity of what I have done in the program. The include image part of the code is a library in Pyret that shows us the images when I program them. The second important part of the program is that in the section where it says "include image-structs" This part of the code gave me the "Old Glory Blue" and "Old Glory Red" I needed in order to get the exact color of the flag. In order to actually put the Include image-structs section to good use, I used a function within the library called "color" which took in 4 numbers that applied certain areas of code to insert certain pigments in order to create the color I needed. I just searched the RGB code to insert it into the program and made sure that the color was solid. This later comes into use in the part of the code were I defined the basic shapes of the program and when I was programing this part of the program, I already had the colors I needed and a name for the function so all I had to do was insert the name in the fuction that will produce the image and the color was now part of the code. The hard part was figuring out how to get the place image function to work and my theory on why the size variable doesn't work the way I wanted it to is because the way I programed this part of the program is what messed up the sizing part I talked about earlier. The fact that I used specific numbers in my place-image function is what caused the size variable to not work properly since the place-image function is just keeping the specific numbers I put and this is why this part of the code cant update with the rest of it.
 
## Program code

```
include image
include image-structs
red-stripe = color(191, 10, 48, 1)
blue-stripe =  color(0, 40, 104,1)

size = 200
width = size * 1.9
height = size * 1
SH =  height / 13
BW = size * 0.5385
BL = size * 0.76
UH = height * (7 / 13) 
UW = width * 	0.76


RR = rectangle(width, height, "solid",  red-stripe)
WS = rectangle(width, SH, "solid", "white")
BR = rectangle(BL, BW, "solid", blue-stripe)


S1 = place-image(WS,width / 2,SH *  1.5, RR)
S2 = place-image(WS, width / 2, SH * 3.5, S1)
S3 = place-image(WS, width / 2, SH * 5.5, S2)
S4 = place-image(WS, width / 2, SH * 7.5, S3)
S5 = place-image(WS, width / 2, SH * 9.5, S4)
S6 = place-image(WS, width / 2, SH * 11.5, S5)
BR1 = place-image(BR, UH / 1.6 , UW / 5.41, S6)

```
