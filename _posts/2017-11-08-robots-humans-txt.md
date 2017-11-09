---
layout: post
title:  "robots.txt and humans.txt"
date:   2017-11-08 11:18 +0100
categories: Webdev
author: Filip Gal
comments: true
---

### What humans.txt and robots.txt is and how I used them. <!--more-->

**humans.txt**

The humans.txt contains information about the origin of the website, the team or person behind it, special thanks, and what different programs and software was used in the making of the website.
How I used it is pretty straight forward, I included my name, and my github account, and mentioned what standards, programs, and softwares that was used.

**robots.txt**

robots.txt is just a text file where you can set different parameters, or instructions if you will, which tells web crawlers if they are allowed to access a certain file or folder on your website.

But to clarify, the robots.txt file just gives out instructions. Well behaved crawlers and robots will respect what is said in the .txt file, but this doesn't mean that all crawlers will. Ill mannered robots will still search through websites, one example is to search for emails to add to a botnet that sends spam mail.

It might be a lazy approach, but I went ahead and chose to instruct all well behaving crawlers that the entire site is off limits. I don't feel I have any need for crawlers to search my site for information since at the moment, it is only for school purposes.