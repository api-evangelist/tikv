---
title: "Getting Started with JuiceFS Using TiKV"
url: "https://tikv.org/blog/tikv-on-juicefs/"
date: "Wed, 08 Sep 2021 00:00:00 +0000"
author: ""
feed_url: "https://tikv.org/blog/index.xml"
---
As a cloud-native distributed storage system, JuiceFS was designed into a plug-in structure at the beginning of its birth to ensure that new technologies can be continuously integrated into the JuiceFS ecosystem. According to your needs, you can flexibly choose two core components, the data storage engine and the metadata engine.
The data storage engine is mainly object storage. It supports almost all public and private cloud object storage services, as well as KV storage, WebDAV, and local disks.
