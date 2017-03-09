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

I have only got up to the first part of digits so I have not yet run into too many problems. Although, I did run into one situation, not necessarily a problem, but could easily turn into one. When committing changes to GitHub, I realized there were over thousands of “changes” git was requesting to commit. I thought this looked a bit funky, but I brushed it off and thought “eh, it shouldn’t be too bad”. I later found out from my professor on slack that this should not be happening. It should only be committing no more than a few hundred. I discovered the root of this problem was from not including the .gitignore file into my project. I have a Mac, so most of the times, . files are hidden, which is why I forgot to include. I inserted this file through the command line into my project and after that, never had to commit over a thousand changes through git. If I continued to do this, it could have slowed my computer down and I would be sitting there wondering what is making my project take so long to load or install. This could have been a bad situation so I easily dodged a bullet.

