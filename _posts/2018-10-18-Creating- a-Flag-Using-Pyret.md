---
layout: post
title: Creating a Flag With Pyret
date: 2018-10-18
---

This week in computer science was exciting. For the first time in weeks, it felt like we were finally applying what we are learning and use what we learned to create a computer program. We started creating our flags using a coding language called Pyret. as you can see, I created the Puerto Rican flag below. I personally think it turned out great!
<br/>
![My Flag](/images/FLAG.png)
<br/>
We studied new contracts that would show us how to create and "overlap" images using a familiar function we briefly discussed last year called "place-image". What place image does is a bit self explanatory, It takes two images and puts them on top of eachother. The contract rule for place-image would be:

<strong>place-image</strong>::(img 1:: image
  <br/>
  X::Number
  <br/>
  Y::Number
  <br/>
  scene::image)->
  <br/>
  
The contract above explains the info that the computer needs in order to produce an image with more then one image inside of it. It first takes in an image, then it takes in the cordinates of where that image needs to be, then places that image on a "scene" or in other words places image 1 on image 2. My code uses a series of place-image funtions and other functions such as Circle, rectangle, and star. Now something challenging about all this was that I wasn't sure at first how to place images on top of other images. At the beginning of the week I was attempting to use another function called "overlay-align" and it just wasn't working. It was not until I realized during an activity called "pair programing" that it would be easier to give functions names and it would be easier to use the place-image function by using these names so I won't need to keep going back and repeating functions and re-writing them. 

Pair programing was both a struggle and helpful. The reason why I say this is because at first, It was really hard to communicate with another person and have them understand what I was trying to say and was pretty annoying that I couldn't just do the programming myself. But after some time it became more and more easier to convey my ideas to my parter and complete most of the tasks in one period.

Another challenge during this project was trying to figure out how to use the place image function in a way that will take two white rectangles and place them on top of a red rectangle and divide the red rectangle into 4 equal pieces to represent the stripes on the flag which took a lot of trial and error. There was most likely an easier way to make the stripes however after some time, the stripes looked good on the flag.





