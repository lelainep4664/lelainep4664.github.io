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
one thing I wish I did during this project was ask for more help from my teacher instead of solely trying to figure out the problem by myself.
-   What questions, strategies, help from peers or teacher, or thinking got you to this point? _then delete this instruction_

<!--- Delete this comment and add your writing -->


## Explain your code.
<br/>
include image<br/>
include image-structs<br/>
red-stripe = color(191, 10, 48, 1)<br/>
blue-stripe =  color(0, 40, 104,1)<br/>
<br/>
size = 200<br/>
width = size * 1.9<br/>
height = size * 1<br/>
SH =  height / 13<br/>
BW = size * 0.5385<br/>
BL = size * 0.76<br/>
UH = height * (7 / 13) <br/>
UW = width * 	0.76<br/>
<br/>
in the first part of the argument, the 
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

```
Insert 10-15 line code section here _then delete this instruction_
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
