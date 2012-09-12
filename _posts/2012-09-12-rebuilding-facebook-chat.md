---
layout: main
title: "Rebuilding Facebook Chat"
category: speaker
---

# [{{ page.title }}]({{ page.url }})

Speaker: <a href="https://www.facebook.com/wolffiex">Adam Wolff</a>

Facebook chat used to be notoriously unreliable. User complaints about
disconnection, incorrect message counts, and missed messages dominated
Facebook's overall product feedback. New code frequently caused
regressions because of untracked dependencies in our ginormous,
monolithic codebase.

Not long ago, a small team set out to fix this by introducing
modularity and unit testing. Along the way, we developed an approach
that abandoned conventional MVC in favor of a functional style. The
rewrite was a success: we were able to improve every important metric
for chat, and we have continued to add features without causing
regressions. Come learn about how we did it.
