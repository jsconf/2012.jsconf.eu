---
layout: main
title: "Faster than C? Parsing Node.js Streams!"
category: speaker
---

# [{{ page.title }}]({{ page.url }})

<iframe width="560" height="315" src="http://www.youtube.com/embed/Kdwwvps4J9A" frameborder="0" allowfullscreen="true">
</iframe>

<a href="http://felixge.de/"><img src="/images/felix-geisendoerfer.png" class="speaker" alt="Felix Geisendörfer"></a>
Speaker: <a href="http://felixge.de/">Felix Geisendörfer</a>

In 2010 I wrote the first MySQL driver for node.js. I did it in pure JavaScript. It was fast. It was fun.

A few month later, node addons using libmysql showed up in npm. They were much faster. It sucked.

In 2012 I had enough and went back to to the drawing board resulting in a much faster parser.

This talk will introduce you to the art of high performance binary stream parsing in node.js.
