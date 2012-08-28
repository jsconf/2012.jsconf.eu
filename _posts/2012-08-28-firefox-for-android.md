---
layout: main
title: "Firefox for Android"
category: speaker
---

# [{{ page.title }}]({{ page.url }})

<a href="http://blog.margaretleibovic.com/"><img src="/images/margaret-leibovic.png" class="speaker" alt="Margaret Leibovic"></a>
Speaker: <a href="http://blog.margaretleibovic.com/">Margaret Leibovic</a>

The Firefox desktop UI is powered by JS and Mozilla's XUL platform, and in our first attempt to port Firefox over to Android, we used essentially the same architecture. However, drawing our own XUL-based UI killed startup time, responsiveness and memory use on Android, so about 10 months ago we decided start over with an entirely native Android UI.

We still use Gecko to render the same web experience you get on desktop, and a lot of the front-end browser logic is still written in JS, but we use a custom JSON message loop to communicate with a native Android UI written in Java and XML. Add-ons are an important part of the Mozilla story, so we also added JS APIs to allow add-on authors to manipulate this new native UI.

I'll talk about the architecture of our app, challenges we faced, and how you can get involved with the project (including writing add-ons entirely in JS!).
