---
layout: essay
type: essay
title: C'mon Guys, Have Some Standards
date: 2017-02-09
labels:
  - coding standards
---

<img class="ui medium left floated image" src="../images/code-review-2.jpg">

## Coding Standards

When it comes to coding, people often think the only important thing is to simply implement the task successfully. Definitely yes, writing code that works is the number one thing a programmer should focus on. I mean, what good is a piece of code that doesn't serve its intended purpose? Many people overlook the importance of formatting and style. Just like writing an essay when you're coding you need to be mindful of where to put spaces, where to indent, and when to enter a new line are all very crucial. An essay may be very interesting, engaging, and informative, but if everything were written in one long paragraph, the formatting alone in this case would be enough to deter someone from reading the essay in its entirety.  It quickly loses its value.

Imagine you're thrown into a software engineering project midway and need to get acquainted with thousands of lines of code, daunting, right? Now imagine that those lines of code are not properly named, spaced, indented, or commented. Suddenly just trying to read through the code becomes another task in itself due to the lack of proper formatting standards. We can give a messy programmer the benefit of the doubt and say that their programs execute and run properly, but their formatting flaw will eventually lead to problems in the future. You might be asking yourself, "If the program works, then what problems could you possibly encounter in the future?". Great question. Anyone who writes software knows that eventually features will need to be added, or taken away based on the needs of their client. If the readability of your software comes into question, it will inevitably slow down the entire process, which in turn could cause some major problems.

Herein lies the beauty of having coding standards such as ESLint which places an emphasis appearance. That being said, coding standards are much more than merely having your code look clean. Having coding standards aids in keeping projects harmonized as if they were being written by a single person. Coding standards ultimately will help to prevent and/or find mistakes that many programmers will often times overlook. 

From a personal standpoint working with ESLint helped me to produce better code that minimized many complications that otherwise could have arose. For example, ESLint would notify me if I never reassigned a variable, and would then suggest I change it to a "const" instead of "let". Seeing this happen helped me realize what variables were meant to stay constant and prevented me from changing them if I got confused throughout my code. ESLint also specifies when to delete unnecessary lines of code, which in turn helped me to create code with a smaller footprint, which again aided in my codes readability. Although these finer nuisances may seem small, it adds up and became especially helpful when working on larger scale projects. So while for some, coding standards may seem like an annoyance, I learned that they do not only help you to produce cleaner code, but overall helps the software engineering process to be smoother when working in groups.


