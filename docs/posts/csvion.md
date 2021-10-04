---
title: CSVion
image: https://images.unsplash.com/photo-1632163524741-3c2dd85f1814?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2071&q=80
publish: 2021-09-30
type: post
tags:
  - project
  - csvion
categories:
  - projects
readingTime: 3 Minutes
author:
  link: /about
  name: Deniz Aydar
---

So in short, CSVion is intended to make CSV files callable and queryable via a generic Rest API server.

The purpose of this post is to record the progress of the project implementation and begins with the background.

While reading another article about exploits in image processing, I came across the programming language Rust, which could counteract this by thread safety. This seemed interesting and I decided to create a project written in Rust to get familiar with this language. Since I lost the link to the article, I can't elaborate on this aspect but it was the inital start point for this project. (**EDIT** I found later the post: [fuzzing ImageIO](https://googleprojectzero.blogspot.com/2020/04/fuzzing-imageio.html))
But like any interest, I needed a hook for what the project should be about.

For this I thought of another project which would have the appropriate scope. The background with this project was that I once needed an API for a mobile app to develop against. 
I downloaded a data dump and was looking for a solution to make it available as a Rest API. For this, I found several projects, all written in Python from which I selected one and deployed it in a Docker container.


The implementations were very basic and therefore suitable for me as an attempt to realize this approach in another language. Let's see how it goes further.