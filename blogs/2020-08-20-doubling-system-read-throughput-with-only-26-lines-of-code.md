---
title: "Doubling System Read Throughput with Only 26 Lines of Code"
url: "https://tikv.org/blog/double-system-read-throughput/"
date: "Thu, 20 Aug 2020 00:00:00 +0000"
author: ""
feed_url: "https://tikv.org/blog/index.xml"
---
Follower Read is a highlight open-source feature that improves the throughput of the TiKV clients and reduces the load on the Raft leader. To understand how important this feature is, you’ll need a bit of background. TiKV stores data in basic units called Regions.
