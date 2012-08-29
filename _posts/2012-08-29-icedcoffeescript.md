---
layout: main
title: "IcedCoffeeScript"
category: speaker
---

# [{{ page.title }}]({{ page.url }})

<a href="http://maxtaco.github.com/coffee-script/"><img src="/images/maxwell-krohn.jpeg" class="speaker" alt="Maxwell Krohn"></a>
Speaker: <a href="http://maxtaco.github.com/coffee-script/">Maxwell Krohn</a>

I cofounded OkCupid.com back in 2003. It was my fateful decision to base our whole stack on a single-threaded event-based library written in C++.  It sucked; our code was stuffed with callback spaghetti and pyramids of death.  But all of that changed when in 2006, we wrote the "Tame" system for C++, which we presented at USENIX ATC in 2007.  This new system was compatible with the old code, but drastically improved our productivity by allowing straight-line code on either side of an a network call, much like threads supported all along.

Most JavaScript and CoffeeScript systems work like OkCupid's did in 2005.  But two JavaScript systems I've written --- TameJS and IcedCoffeeScript --- change all of that.  They bring the same language primitives to node.js and the browser that Tame brought to OkCupid's C++ libraries.  These primitives are more powerful than threads and more manageable than hand-rolled callback code.  If you give them a chance, they will make your JavaScript projects cleaner, more manageable, more parallel and therefore better performing.
