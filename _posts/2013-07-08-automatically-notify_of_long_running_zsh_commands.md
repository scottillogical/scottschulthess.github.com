---
layout: post
title: "Automatic notifications of long running shell commands"
description: ""
category: 
tags: []
---
{% include JB/setup %}

I've been using a very useful zsh snippet by Juan Germán Castañeda Echevarría
for a while now and I wanted to post this so I'd remember it.

Essentially, whenever any long-running command completes, it executes a growl
notification that tells you whether it succeeds or fails.  It's great for
deployments, unit tests, file copies, and so forth.
{% gist 4557831 %}
