---
title: "Generics and Compile-Time in Rust"
url: "https://tikv.org/blog/generics-compile-time-rust/"
date: "Thu, 17 Sep 2020 00:00:00 +0000"
author: ""
feed_url: "https://tikv.org/blog/index.xml"
---
The Rust programming language compiles fast software slowly.
In this series we explore Rust&rsquo;s compile times within the context of TiKV.
Rust Compile-time Adventures with TiKV: Episode 2 In the previous post in the series we covered Rust&rsquo;s early development history, and how it led to a series of decisions that resulted in a high-performance language that compiles slowly. Over the next few we&rsquo;ll describe in more detail some of the designs in Rust that make compile time slow.
