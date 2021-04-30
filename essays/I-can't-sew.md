---
layout: essay
type: essay
title: Why Would I Need a Design Pattern? I Can't Sew
# All dates must be YYYY-MM-DD format!
date: 2021-04-30
labels:
  - Design patterns
  - Meow Mapper
---

## I'm a Computer Science student, not a . . .

I have only known what design patterns are in a computer science context for approximately 24 hours. Before then, I never would have even thought that the phrase had a computer science context at all – it sounds more like something that would be of interest to a fashion designer, not a burgeoning software developer. Since then, I have taken a deep dive to discover the true depth of the error in my thinking. A design pattern, I have learned, is something designed to make my life easier. It is a solution that I can duplicate to address common problems in my coding given certain similarities in environments. Of course, as soon as I heard this, my interest was piqued; I am still new to software development, so errors abound in my code. Was this a way to help mitigate the problems in my code? Maybe even a panacea for all coding difficulties? Sign me up!


## It’s Not That Easy

But what's that easy? Not design patterns! To my consternation, I discovered design patterns were certainly not an immediate solution to all of my coding woes. Although understanding the various design patterns will unquestionably help me become a more competent software developer, it is certainly no quick fix. As I perused more materials on design patterns, I even realized something else. Far from being a magical new cure-all, design patterns were already in my software developer kit of tricks. It was only the name I was truly coming across for the first time, because the concepts themselves I have used multiple times unknowingly. 

<img class="ui medium left floated image" src="../images/meow.PNG">    

## Meow Mapper

In a project called [Meow Mapper](https://meowmapper.com/) that I created with several friends in JavaScript, we used multiple design patterns. The prototype design pattern was utilized to create classes of objects like "Adopts" and "Snaps", which were used to fill out the respective collections of "Cats to Adopt" and "Cat Snaps" (which are just pictures of cats). These collections were then used to populate their eponymous pages, and let users upload their own pictures of cats to the “Snaps” collection and adopt cats in the “Adopts” collection. We also implemented the public-subscribe design pattern to control what pages users in different roles could see. For example, a user with the role of simply "User" cannot edit the "Adopt a Cat" page or see the "Admin" page, as a user with the role "Admin" can. 

