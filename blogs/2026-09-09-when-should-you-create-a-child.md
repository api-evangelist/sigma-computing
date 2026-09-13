---
title: "When should you create a child?"
url: "https://community.sigmacomputing.com/t/when-should-you-create-a-child/7233#post_3"
date: "2026-09-09"
author: "@david.zingher David Zingher"
feed_url: "https://community.sigmacomputing.com/posts.rss"
---
That can be true! However, since the “child” is really just a layer of SQL wrapped around the query that the parent element represents, it’s no more intensive than running that child element’s SQL all-in-one. Sigma reuses the results of the “inner” query instead of running it again.
