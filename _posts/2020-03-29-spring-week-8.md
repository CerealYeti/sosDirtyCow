---
layout: post
title: Spring Week 8
date: 2020-03-29
---
This week was about testing our VM. If we set it up correctly then we should be able to exploit it with Dirty COW. First we wrote a script to exploit Dirty COW to let us write to a read-only file via proc/self/mem. The first script we wrote didn't work, but the second version did. We officially have a vm that can be exploited with Dirty COW. 
