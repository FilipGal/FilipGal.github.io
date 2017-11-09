---
layout: post
title:  "Open Graph"
date:   2017-11-09 10:59 +0100
categories: Webdev
author: Filip Gal
comments: true
---

#### What is Open Graph? And how did I implement it? <!--more-->

Open Graph was introduced by Facebook in 2010, what it does is that it allows integration between social media and a website. When integrating meta tags to your pages content you can specify which elements of your page you want to be shown when it's shared somewhere. You could for instance use the tag og:title to specify the title to be displayed.

To implement Open Graph, I used a plugin for Jekyll called [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag){:target="_blank"}.
This was a very efficient way of adding metadata tags to my website. If you want to know everything it adds I suggest you read up on it, but some meta tags that it adds are:

* Page description
* Twitter Summary Card metadata
* Open Graph title, site title, and URL

Setting the image and type I found was a bit trickier. For the time being I just included manual tags for `og:image` and `og:type` in the head.html file.