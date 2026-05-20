---
title: "How TiKV reads and writes"
url: "https://tikv.org/blog/how-tikv-reads-writes/"
date: "Fri, 06 Dec 2019 00:00:00 +0000"
author: ""
feed_url: "https://tikv.org/blog/index.xml"
---
This article introduces in detail how TiKV handles read and write operations. Together we will explore how TiKV, as a distributed key-value (KV) database, stores the data contained in a write request and how it retrieves the corresponding data with consistency guaranteed. Before you read it Before we begin, we need to introduce some essential concepts of TiKV to help you fully understand the process.
