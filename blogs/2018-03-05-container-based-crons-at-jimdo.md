---
title: "Container Based Crons at Jimdo"
url: "https://dev.jimdoweb.com/2018/03/05/container-based-crons-at-jimdo/"
date: "2018-03-05"
feed_url: "https://dev.jimdoweb.com/rss/blog"
---
When building a large-scale web service one of the things you come across sooner or later is automatically running tasks and Jimdo is no exception to this. For us these tasks can target multiple goals like renewing SSL certificates, processing payments, or calculating scaling information of our infrastructure. The way we execute and monitor them has been an ever changing topic for us and we iterated and evolved our ideas over the last years.
