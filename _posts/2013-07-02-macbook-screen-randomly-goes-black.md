---
layout: post
title: "2010 Macbook Screen Randomly Goes Black"
description: ""
category: 
tags: []
---
{% include JB/setup %}

A few weeks ago, about once a day, my 2010 15" Macbook Pro screen would go black.  
The keyboard lights would stay on, but I'd have to restart it to continue
working.

After a lot of research, I discovered this was related to the discrete graphics
card driver freaking out.  

One thing I noticed after I installed the utility GfxCardStatus was that when I
was running Chrome, the Macbook was **always** using the discrete graphics card. 

To solve this, open chrome with the correct command line flag, added to address
this very issue.

` 
  open -a /Applications/Google\ Chrome.app/ --args
--gpu-switching=force_integrated
`
