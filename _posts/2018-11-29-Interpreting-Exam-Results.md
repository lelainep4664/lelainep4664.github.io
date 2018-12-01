---
layout: post
title: Interpreting Exam results 
date: 2018-11-29
---

Earlier in the week, we took a midterm exam that covered most of what we have been learning so far in the Fall semester. In my opinion, the exam was not too difficult. Over the past 2 days we were talking about analyzing the attributes of the exam and identfying the different parts of how we will be graded and what mastery skills were tested. The test was split up into 2 versions and each had the same questions and answers except the question numbers and order of the answer choices were changed around. In this reflection, we will look at one of the questions from the exam and analyze the different parts of the question. 

The question we will be looking at today is question 10 where it stated the following:
<br/>
10.) What is the value of the following expression?
<br/>
(string-length("helloWorld!") + (5 + 4)) / 2
<br/>
a.)10
<br/>
b.)20
<br/>
c.)40
<br/>
d.)none of the above
<br/>
The correct answer was (a). This question tested Mastery skill 1 on the practioner level. MS1 assesed if are able to use tools and terms such as functions, keywords and evaluating expressions and checking if the application matches the contract created. We know the question was a PRAC level question because we needed to apply more than one step to solve a given problem. This problem used about 4 steps to solve it which further proves this was a practioner level question. One reason to tell that the problem is testing mastery skill 1 because it never asked what TYPE of data would represent like MS3 "designing new tools" we also weren't taking any new information and turning it into computable data to make this MS3. We also know that the question was not testing MS5 "designing funtions" because we were not designing funtions or identifying abstractions or changes in data or assessing contracts, test cases, or definitions. 

looking back at solving our problem, we can see that we are evaluating expressions by looking at the given values. Im pretty sure I got the question wrong on the actual baseline however, now looking at the question and the answer and knowing what was actually being assessed, I see how the correct answer to the question was 10. Heres how I came about solving the problem. 
<br/>

1.) By seeing the function "string-length" I figured it meant that it took the number of characters inside of the string and evaluated that into a number and that number would be 11 because looking at all the characters in the string, you have 10 letters that make up "helloWorld" and then there is an exclamation mark which also counts as another character which evaluates to 11.
<br/>

2.) Then I saw that at the end of the expression, there were more number values. By using basic knowledge of math, I saw that there were parentheses so I thought back to math using the order of operations and put my own spin on it where instead of using PEMDAS (Parentheses Exponents Multiplication Division Addition Subtraction) it was more like "FPEMDAS" were the "F" would mean Function so I knew to solve the parentheses part of the problem next. so I added (5+4) which is 9.
<br/>

3.) Thinking back to computational algebra last year, I remembered how the circle of evaluation worked and saw that the given expression had 2 parentheses which marked the end of 2 arguments meaning the next part of the question would be to add the number that the function "string-length" would produce as well as the value of (5+4)  and got 20 because 11 + 9 is 20.
<br/>

4.) Last, the final part of the expression states 




