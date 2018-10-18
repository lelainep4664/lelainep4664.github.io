---
layout: post
title: Creating a Flag With Pyret
date: 2018-10-18
---

This week in computer science was exciting. For the first time in weeks, it felt like we were finally applying what we are learning and use what we learned to create a computer program. We studied new contracts that would show us how to create and "overlap" images using a familiar function we briefly discussed last year called "place-image". What place image does is a bit self explanatory, It takes two images and puts them on top of eachother. The contract rule for place-image would be:

<strong>place-image</strong>::(img 1:: image
  <br/>
  X::Number
  <br/>
  Y::Number
  <br/>
  scene::image)->
