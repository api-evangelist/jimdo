---
title: "Wait for it...a deep dive into Espresso's Idling Resources"
url: "https://dev.jimdoweb.com/2014/05/09/wait-for-it-a-deep-dive-into-espresso-s-idling-resources/"
date: "2014-05-09"
feed_url: "https://dev.jimdoweb.com/rss/blog"
---
(A first draft of this blog post originally appeared on my personal blog: Wait for It…a Deep Dive in Espresso's Idling Resources ) One of the challenges developers have to face when writing UI tests is waiting for asynchronous computations or I/O operations to be completed. In this post I'll describe how I solved that problem using the Espresso testing framework and a few gotchas I learned. I assume you're already familiar with Espresso, so I won't describe the philosophy behind it but instead I'll just focus on how to solve that problem the Espresso way.
