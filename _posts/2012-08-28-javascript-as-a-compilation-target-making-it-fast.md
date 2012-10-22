---
layout: main
title: "JavaScript as a compilation target - Making it fast"
category: speaker
---

# [{{ page.title }}]({{ page.url }})

<iframe width="560" height="315" src="http://www.youtube.com/embed/d-xVOke3ync" frameborder="0" allowfullscreen="true">
</iframe>

<a href="http://florian.loitsch.com"><img src="/images/florian-loitsch.jpeg" class="speaker" alt="Florian Loitsch"></a>
Speaker: <a href="http://florian.loitsch.com">Florian Loitsch</a>

We would like to present dart2js, our Dart-to-JavaScript compiler. We have implemented many optimization techniques and in this talk we would like to present some of them.
In particular we want to discuss *tree-shaking, speculative optimizations, and local SSA-based optimizations.* While our compiler is specialized for Dart, most of the optimization techniques could be adapted for other languages and are therefore interesting to anyone targeting JavaScript as a compilation target.
