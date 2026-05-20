---
title: "Implement Raft in Rust"
url: "https://tikv.org/blog/implement-raft-in-rust/"
date: "Thu, 14 May 2020 00:00:00 +0000"
author: ""
feed_url: "https://tikv.org/blog/index.xml"
---
Consensus is one of the most important challenges in designing and building distributed systems–how to make sure multiple nodes (or agents, processes, threads, tasks, participants, etc.) in a group agree on a specific value proposed by at least one of the nodes. As an open-source distributed transactional key-value database, TiKV uses the Raft Consensus Algorithm to ensure data consistency, auto-failover, and fault tolerance. TiKV has thus far been used by almost 1000 adopters in their production environments in a wide range of industries, from e-commerce and food delivery, to fintech,…
