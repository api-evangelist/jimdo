---
title: "Simple service discovery using AWS Private Hosted Zones"
url: "https://dev.jimdoweb.com/2015/04/23/simple-service-discovery-using-aws-private-hosted-zones/"
date: "2015-04-23"
feed_url: "https://dev.jimdoweb.com/rss/blog"
---
A rather simple, but effective and easy-to-setup service discovery (SD) mechanism with near-zero maintenance costs can be build by utilizing the AWS Private Hosted Zone (PHZ) feature. PHZs allows you to connect a Route53 Hosted Zone to a VPC, which in turn means that DNS records in that zone are only visible to attached VPCs. Before digging deeper in the topic, let’s try to find a definition for 'simple service discovery'.
