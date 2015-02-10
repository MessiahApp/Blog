---
layout: page
permalink: /about/index.html
title: We are the Messiahs
tags: [Messiah, App, iOS, Android]
#imagefeature: fourseasons.jpg
chart: true
---
<figure>
  <img src="{{ site.url }}/images/MessiahCover.jpg" alt="The Messiah Cover">
  <figcaption>The Messiah</figcaption>
</figure>

{% assign total_words = 0 %}
{% assign total_readtime = 0 %}
{% assign featuredcount = 0 %}
{% assign statuscount = 0 %}

{% for post in site.posts %}
    {% assign post_words = post.content | strip_html | number_of_words %}
    {% assign readtime = post_words | append: '.0' | divided_by:200 %}
    {% assign total_words = total_words | plus: post_words %}
    {% assign total_readtime = total_readtime | plus: readtime %}
    {% if post.featured %}
    {% assign featuredcount = featuredcount | plus: 1 %}
    {% endif %}
{% endfor %}
Hi folks. I'm **Muhammad Haroon Baig**, a slash coder and a techie guy digging deep into various new tech-related stuff with great enthusiasm to try new gadgets. I usually spend a lot of time coding in Python and Swift, configuring Linux and exploring Django.

Curretly, I'm a Microsoft Student Partner, a Computer Systems Engineer and a researcher. One of my findings was published in the International Conference on Space 2014, held in Islamabad.

*[ESE]: Electrical and Systems Engineering
*[SEAS]: School of Engineering and Applied Science
*[MIT]: Massachusetts Institute of Technology
*[EECS]: Electrical and Computer Engineering
*[UPENN]: University of Pennsylvania

<figure>
	<img src="{{ site.url }}/images/Microsoft_pic.jpg" alt="Hossain Mohammad Faysal">
	<figcaption>At Microsoft office, Islamabad</figcaption>
</figure>

I was born in Pakistan, which is one of the loveliest countries with natures best gifts. From snowy peaks to vast deserts. It has shown the will and strength to fight worst terrorism of recent times and has contained it for peace of world.

But over the years, I noticed that somehow, along the way, software designed to help us be creative, actually made us less creative. That's because we believe our best ideas emerge when we use pencils and paper.
So I set out to build tools that work the way I do.


For
the makers,  
the creators,  
the discoverers,  
the original thinkers,  
***This is the space to create.***
