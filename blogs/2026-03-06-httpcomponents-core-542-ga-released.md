---
title: "HttpComponents Core 5.4.2 GA released"
url: "https://hc.apache.org/news.html"
date: "2026-03-06"
author: ""
feed_url: "https://hc.apache.org/news.html"
---
This maintenance release fixes a bug in the lax connection pool where expired connection cleanup fails to update the number of available connections, potentially causing the client to eventually deadlock. Two other fixes are included as well, one for a memory leak in the implementation of HTTP/2 stream priority and one in the parseLenient method, which should ignore illegal character names.
