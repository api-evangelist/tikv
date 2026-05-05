---
title: "SIG-txn reading group, Nov + Dev 2020"
url: "https://tikv.org/blog/sig-txn-reading-group-nov-20/"
date: "Wed, 04 Nov 2020 00:00:00 +0000"
author: ""
feed_url: "https://tikv.org/blog/index.xml"
---
The TiKV transactions SIG is starting up its reading group. We&rsquo;ll try to read and discuss a paper each month. If you&rsquo;re interested in research in distributed transactions, come join in!
We&rsquo;ll start by reading &lsquo;Industrial-Strength OLTP Using Main Memory and Many Cores&rsquo;, by Avni et al. at Huawei Research Centre. It was published in the proceedings of VLDB 2020 and you can download it from them.
The paper describes a new storage engine for GaussDB (an HTAP (OLTP + OLAP) database from Huawei), that includes a transaction system, and a JIT compiler for SQL processing.
