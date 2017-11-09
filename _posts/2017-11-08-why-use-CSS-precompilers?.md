---
layout: post
title:  "Why use CSS precompilers?"
date:   2017-11-08 08:00 +0100
categories: Webdev
author: Filip Gal
comments: true
---

### What's so great about css pre-compilers? <!--more--> 

One part of this assignment was for us to use a CSS preprocessor, or `sass` to be more precise. Using `sass` provides many quality of life improvements over regular css.

sass allows for several features that plain 'ol css does not provide, two very handy features are declaring variables and nesting your syntax. So far, variables have given me the most value, being able to declare a color, and assign it to a variable, makes changing it site-wide a breeze. Compare that to css where you have to check though your code and change every instance manually...

* Pros
    * Being able to split up your css in multiple partials makes it easier to organize
    * Cleaner syntax with nesting divs
    * Way easier to maintain using variables

* Cons

    * Using sass requires a bit more effort on your part, mainly with installing necessary components. If you're using regular css there's nothing more to it than to name a file `example.css` and then hammer away at the keyboard. However, I think that the only time when you should use regular css is when you're just starting out, as you learn more and become comfortable css, you really should start using a pre-compiler. 

    * **You might get used to it**. This isn't the end of the world, but if you're then one day placed in front of a project where plain css is used, there might be some head scratching involed. Is this a bad thing? Not really to be honest, the payoff from using a pre-processor far outweighs the possibility of you having to use plain css one day.

Some techniques that I have used have been variable defaults (`!default`) and nesting syntax.