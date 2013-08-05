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
An agile tenant.  For decisions you are'nt positive about, from a business-requirement standpoint or an design implementation standpoint, the best decision is often to avoid making one.  Start out with a first take an add onto it slowly, but avoid adding a lot of structure up front.  Most likely, you'll be wrong.  In some codebases those early design mistakes stay around for a long time.

**Keep your deployments smooth and consistent**  
Deployments should require just running a command.  Advanced users deploy from chat rooms, but a simple command line script works.  [Here's](https://gist.github.com/scottschulthess/5136935) a example bash script that does a heroku deploy, optionally running tests.  

**Fix bugs when you find them**  
Sometimes your workday ends up looking like [this](http://i.minus.com/ibaDjk7AeIcvxv.gif).  Unfortunately, with programming, often best time to fix a bug is right now.   Some bugs, you won't be able to reproduce again.  I usually learn a lot about a system when I encounter a suprising bug.
