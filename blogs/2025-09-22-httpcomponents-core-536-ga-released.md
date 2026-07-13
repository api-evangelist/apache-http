---
title: "HttpComponents Core 5.3.6 GA released"
url: "https://hc.apache.org/news.html"
date: "2025-09-22"
author: ""
feed_url: "https://hc.apache.org/news.html"
---
This maintenance release fixes a regression introduced by the previous release that can cause a temporary I/O spin during HTTP/2 connection shutdown in case the opposite endpoint fails to send a GOAWAY frame, and also fixes several bugs related to abnormal termination of HTTP/2 connections found since the last release.
