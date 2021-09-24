---
title: Creating a blog site
image: https://images.unsplash.com/photo-1598449356475-b9f71db7d847?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80
publish: 2021-09-24
type: post
tags:
  - initial page
  - blog
categories:
  - general
readingTime: 3 Minutes
author:
  link: /about
  name: Deniz Aydar
---


While browsing Hacker News someday, I came across an interesting post about the possibility of [abusing the Chrome Devtool](https://medium.com/@weizmangal/javascript-anti-debugging-some-next-level-sh-t-part-2-abusing-chromium-devtools-scope-pane-b2796c00331d) and how the author used this to write a library to counter it. After reading this article, out of curiosity, I looked at his blog which was given in the post as the [original source](https://weizman.github.io/?about). 

I looked around a bit and noticed that the url was composed of his username and the page GitHub. More specifically, the username was specified as the subdomain and GitHub was specified as the domain. Since I had seen this before, I did some research and found out that this is made possible through a website hosting service called GitHub Pages. This has existed for several years and has been around for a while, so it's nothing new to use. Nevertheless, I saw in the fact that I had not noticed it, the chance to try it out. 


__So I started to work on the tutorial first.__ The structure was explained and *Jekyll* was recommended to be used as a static site generator. I tried it but didn't like the usage, so I tried a generic *Vue* web application for this purpose. In the middle of the implementation, I discovered *Vuepress* which is a Vue framework for blogging among other things. This seemed fitting for a page that is supposed to profile my persona, so I switched frameworks again. Here I struggled with versioning and deploy, as this was not so directly implementable without causing further problems. When I could solve this, I chose a suitable theme and had my first blogging site ready. 

Now I have the opportunity to capture insights I gather through my work, studies or hobbies in a digital online form. The whole thing is supposed to give me an overview about occurred problems and their possible solutions or approaches but also to enable the some reader to help himself and possibly others with further information.


The initial step for the page was created with this. 
