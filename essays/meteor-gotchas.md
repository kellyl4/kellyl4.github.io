---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

## Meteor Problems

I have only got up to the first part of digits so I have not yet run into too many problems. Although, I did run into one situation, not necessarily a problem, but could easily turn into one. When committing changes to GitHub, I realized there were over thousands of “changes” git was requesting to commit. I thought this looked a bit funky, but I brushed it off and thought “eh, it shouldn’t be too bad”. I later found out from my professor on slack that this should not be happening. It should only be committing no more than a few hundred. I discovered the root of this problem was from not including the .gitignore file into my project. I have a Mac, so most of the times, dot files are hidden, which is why I forgot to include it. I inserted this file through the command line into my project and after that, never had to commit over a thousand changes through git again. If I continued to do this, it could have slowed my computer down and I would be sitting there wondering what is making my project take so long to load or install. This could have been a bad situation so I easily dodged a bullet.

## My Blonde Moment With Meteor

Another problem I encountered, which I admit was a really dumb problem, was when I was trying to view the localhost:3000 page to view the changes I have made, it would not load. I couldn’t figure out why it wasn’t displaying my page. I did not really read the text it displayed and just kept tweaking with meteor and my code to try get it to work. I later realized it is because I was trying to run two meteors at a time. The moment I realized, I couldn’t believe I made such a dumb mistake. I guess I had a terminal opened with meteor from when I was working on the project earlier and forgot about it. I closed both the terminal windows and ran meteor again and wallaaaa! And no surprise, it worked! Everything was displaying and back to normal. 