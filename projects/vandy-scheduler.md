---
layout: project
type: project
image: img/vandy-scheduler/rmp-score-narrow.png
title: "Vandy Scheduler"
date: 2023
published: true
labels:
  - Web Scraping
  - Chrome Extension
  - Javascript
summary: "A Chrome Extension that allows students to see rate-professor scores directly on course registration website. Now has 3000 users!"
---

Course registration is a pain. One of my biggest pain points is constantly switching back and forth between YES (our course registration website) and Rate My Professors. So I thought to myself, wouldn't it be great if I can simply see professors' Rate My Prof. scores directly on YES... Maybe there are already tools for that?

Sadly, no. After some searching I found the closest thing is an existing extension VandyScheduler. It used to have similar functionality but the creator graduated, and it has been broken for a long time. However, I think I can fix it.

So I updated its background scraping mechanism to get rate my professor scores, contacted the original developer, and eventually got it fixed. Later, I added the functionality of making professors' names into links that allow students to directly go to their rate my professor page.

## the impact

This is my favorite project. Although it is not difficult technically, it has a tangible impact of helping myself and people around me. After the update, I told everyone around me about this extension, and they all loved it. Now, once in a while I catch glimpses of completely strangers using this extension, and I think I have made something really useful.

## Show me the code

{% gist 4cf8a241e1d5ebf9c9bbf56c9ec5c5dc %}

Here is the link the git repo <a href="https://github.com/quinton22/VandyScheduler"> vandy-scheduler </a>. You can see my contribution from the last few commits!
