---
layout: essay
type: essay
title: "ESLint: Not Bad But Not Good"
# All dates must be YYYY-MM-DD format!
date: 2023-09-21
published: true
labels:
  - Software Engineering
  - ESLint
  - Coding Standards
---

<img width="200px" class="rounded float-start pe-4" src="../img/ics314_ESLint.png">

## The struggles

"This is too frustrating", is what I thought when implementing ESLint on my codes. I need a space here. I don't need a space here. I need a newline here, but you can't put one here. Following these strict rules on my code is such a hassle, especially during WODs. I am the type of person where if I see an error, I try to fix it first before moving on to the next task. So seeing these redlines and errors on my editor makes me panic since I feel like I'd be spending most of my time resolving theses so called errors. For example, while I was working on today's WOD, I was trying to return the average values in an array. Since we're expected to use underscore functions, I attempted to do calculate the average of the numbers all in one line. I was pretty familiar on how to do it from previous practice WODs from JSFiddle. But with the strict rules of ESLint where there is a max of 80 characters in one line, I was forced to initialize a variable which would take the total of all the numbers in the array then return that variable divided by the length of the array. Seeing this rule made me VERY frustrated. I just couldn't follow this coding standard anymore.

## Good Practice

Similarly to every bad news, there are some good news. ESLint can be very frustrating to work with when you are used to coding in your own way. Following this coding standard could help you find better ways to improve the looks of your code. So far I have noticed that including spaces here and there makes my code look cleaner. Having your code look neater can help you find your bugs much quicker. Having this benefit allowed me to reduce my time when I debug my code where previously it would take me quite some time just looking for the nasty bug. Since ESLint is widely used in the industry, many people who you might work with in the future can easily understand your code with little to no clarifications needed. Which is a great thing to have since I personally wouldn't want to be bothered about more coding after commiting a long, frustrating lines of code. 

## After Thoughts

ESLint isn't too bad but at the similarly it takes time to get used to it. In my opinion it is a good practice to have. But again, debugging the actual code would be better to use most of my time in rather than correcting some punctuational errors. The benefit of finding a nasty bug much faster is such a great thing to have. I am able to actually think of what is wrong with the code rather than trying to scroll through the editor hundreds of times figuring out where and why is this part wrong. After some thinking, I now think ESLint is a very good way to introduce to amateur coders. I'm pretty sure graders and/or professors who has to look through students code would agree that introducing this coding standard to students would be a great start. But we just have to remember that not everything is for everyone.
