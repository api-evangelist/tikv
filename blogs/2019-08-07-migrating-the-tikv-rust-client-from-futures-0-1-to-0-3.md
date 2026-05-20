---
title: "Migrating the TiKV Rust client from futures 0.1 to 0.3"
url: "https://tikv.org/blog/client-futures/"
date: "Wed, 07 Aug 2019 00:00:00 +0000"
author: ""
feed_url: "https://tikv.org/blog/index.xml"
---
I recently migrated a small/medium-sized crate from Futures 0.1 to 0.3. It was fairly easy, but there were some tricky bits and some things that were not well documented, so I think it is worth me writing up my experience. The crate I migrated is the Rust client for the TiKV database.
