---
title: "How TiKV Uses \"Lease Read\" to Guarantee High Performances, Strong Consistency and Linearizability"
url: "https://tikv.org/blog/lease-read/"
date: "Thu, 27 Feb 2020 00:00:00 +0000"
author: ""
feed_url: "https://tikv.org/blog/index.xml"
---
TiKV, an open source distributed transactional key-value store (also a Cloud Native Computing Foundation incubating project), uses the Raft consensus algorithm to ensure strong data consistency and high availability. Raft bears many similarities to other consensus algorithms like Paxos in its ability to ensure fault-tolerance and its performance implementations, but generally easier to understand and implement. While our team has written extensively on how Raft is used in TiKV (some examples: Raft in TiKV, the Design and Implementation of Multi-raft, Raft Optimization), one topic we haven’t…
