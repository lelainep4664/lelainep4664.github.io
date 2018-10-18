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
<br/>
<strong>place-image</strong>::(img 1:: image
  <br/>
  X::Number
  <br/>
  Y::Number
  <br/>
  scene::image)->
  <br/>
The contract above explains the info that the computer needs in order to produce an image with more then one image inside of it. It first takes in an image, then it takes in the cordinates of where that image needs to be, then places that image on a "scene" or in other words places image 1 on image 2. My code uses a series of place-image funtions and other functions such as Circle, rectangle, and star. Now something challenging about all this was that I wasn't sure at first how to place images on top of other images. At the beginning of the week I was attempting to use another function called "overlay-align" and it just wasn't working. It was not until I realized during an activity called "pair programing" that it would be easier to give functions names and it would be easier to use the place-image function by using these names so I won't need to keep going back and repeating functions and re-writing them.
<br/>
Another challenge during this project was 





