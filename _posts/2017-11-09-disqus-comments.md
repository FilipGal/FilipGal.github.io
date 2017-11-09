---
layout: post
title:  "How I used Disqus to implement comments"
date:   2017-11-09 10:07 +0100
categories: Webdev
author: Filip Gal
comments: true
---

#### Disqus is a really efficient tool for implementing comments on your website <!--more-->

You probably already got it figured out, but to implement comments on my website, I used [Disqus](https://disqus.com/){:target="_blank"}.

To make it work I first had to publish my site at Github pages, then simply go to Disqus website and type in all the necessary information. A problem I had at first was that a comment on one post appeared in the comments for all the other posts. The Disqus code when that problem occured looked as follows:

{% highlight javascript %}
{% raw %}
this.page.url = "filipgal.github.io";
this.page.identifier = "";
{% endraw %}
{% endhighlight %}

To make it work, I just had to make a slight modification:

{% highlight javascript %}
{% raw %}
this.page.url = "{{ site.url }}{{ page.url }}";
this.page.identifier = "{{ page.url }}";
{% endraw %}
{% endhighlight %}
