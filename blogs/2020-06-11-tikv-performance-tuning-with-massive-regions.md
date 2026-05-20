---
title: "TiKV Performance Tuning with Massive Regions"
url: "https://tikv.org/blog/tune-with-massive-regions-in-tikv/"
date: "Thu, 11 Jun 2020 00:00:00 +0000"
author: ""
feed_url: "https://tikv.org/blog/index.xml"
---
In TiKV clients, data is split into Regions, each storing data for a specific key range. These Regions are distributed among multiple TiKV instances. As data is written into a cluster, millions of or even tens of millions of Regions are created.
