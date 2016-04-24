# The Humboldt Data Science website, built using Jekyll


# How to update add a new post (new class)

Simply go to the _posts directory and create a new file named YYYY-MM-DD-FILENAME.md

(md means Markdown, with enables to easily create webpages, see e.g. [this](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet))

the file must starts with 
```
---
layout: post
title: YOUR TITLE HERE
---

your markdown text here which will be visible in the preview of the class 

<!--more-->

more text here only accessible if you clic on the lesson's page...
```
The post will then directly be visible in the "classes" except if you  add `visible: false` in the header of your new post. 

**Done**

