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
  <figcaption>The Messiah Badge</figcaption>
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
Messiah is a civic startup which has a citizen-centric support model. Messiah is an emergency first responder app designed to relay distress signal for the user in the case of an accident or emergency. Messiah relies on a community of Users (Samaritans) Which help each other in the case of emergencies. Messiah started off as a civic app in featured in the Peshawar Fellowship program.Messiah's mission is to make cities safer and use ICT technologies to Respond to Emergencies in the shortest time possible.

*[ESE]: Electrical and Systems Engineering
*[SEAS]: School of Engineering and Applied Science
*[MIT]: Massachusetts Institute of Technology
*[EECS]: Electrical and Computer Engineering
*[UPENN]: University of Pennsylvania

<figure>
	<img src="{{ site.url }}/images/fellowship.jpg" alt="We at fellowship program">
	<figcaption>At Fellowship Program</figcaption>
</figure>

A city like Peshawar ends up in world news daily, mostly because of the terror threats and challenges it faces. But its irrepressible citizens find hope in other areas of progress. They rise to most challenges and resiliently look forward to doing more. The same passion is the fuel behind the Peshawar Fellowship Program. The program is 4 weeks old, but much has transpired in those 4 weeks moving at a very dynamic pace. We were happy to be part of this great Fellowship Program.
