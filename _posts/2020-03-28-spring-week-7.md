---
layout: post
title: Spring Week 7
date: 2020-03-28
---
This week we focused on setting up a vm as an exploitable environment. We chose Ubuntu 14.04 because it works for a couple different exploits that we want to run and it is still a somewhat relevant OS to use in the present day. The first exploit that we want to focus on a privlege escalation hack called Dirty Cow. For this exploit we needed a specific kernerl version running on our OS, so we researched which one we would need and then we rolled back the kernel version to 3.13.0-98-generic, which was the latest Ubuntu kernel version that wasn't patched for Dirty Cow. 
