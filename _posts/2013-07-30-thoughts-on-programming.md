---
layout: post
title: "A few of programming thoughts"
description: ""
category: 
tags: []
---

**Don't use add a database table if you don't have to**  
Your fellow programmers will be a lot more comfortable removing code than removing a database table.  Odds are, if your feature goes unused and gets removed, your table will stay to confuse other coders for centuries.

**Delay design decisions**  
An agile tenant.  For decisions you are not sure about, sometimes the best thing to do is to put it off.  Exploration can be the key here.  Start out with a first take an add onto it slowly, but avoid adding a lot of structure up front.  Most likely, you'll be wrong.  In some codebases those early design mistakes stay around for a long time.

**Keep your deployments smooth and consistent**  
Deployments should require just running a command.  [Here's](https://gist.github.com/scottschulthess/5136935) a example bash script that does a heroku deploy.

**Fix bugs when you find them**  
As a programmer, sometimes your workday ends up looking like [this](http://i.minus.com/ibaDjk7AeIcvxv.gif).  

The scenario is that I'll be working on a feature and encounter the bug.  If the bug is surprising to me, often times, I'll pause what work I was doing on the feature just to investigate this unforeseen issue.  During these explorations I often learn a lot about how system works that can aid me in the future.
