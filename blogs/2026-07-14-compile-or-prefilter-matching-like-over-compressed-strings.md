---
title: "Compile or Prefilter? Matching LIKE over Compressed Strings"
url: "https://spiraldb.com/blog/compile-or-prefilter-like-over-strings"
date: "2026-07-14"
author: "Martin Prammer"
feed_url: "https://spiraldb.com/rss/feed.xml"
---
Two teams independently built SQL LIKE over FSST-compressed strings: Vortex prefilters candidates, TU Munich compiles the pattern. One experiment across seven x86 generations maps where each wins, where they cross, and why the two hot loops belong in one system.
