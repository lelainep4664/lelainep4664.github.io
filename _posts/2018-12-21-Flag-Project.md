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
one thing I wish I did during this project was ask for more help from my teacher instead of solely trying to figure out the problem by myself. I asked one of my peers who had the same Flag as I and asked them how they went about creating the stripes without them giving me the exact code. After listening to their process, it was more easier to understand. Another thing that brought me the exact colors of the flag was asking how to use the image-structs library in Pyret in order for me to create colors of my own using the exact RGB colors of the United states flag. The biggest strategy I used when creating the flag was just defining all of the proportions and then naming them in order to make it easier to use them later. 


## Explain your code.

In the first part of the argument in the code below, I used a simple code that my teacher showed us in class where we used the size variable in order to create a function that will 
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

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

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 

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
