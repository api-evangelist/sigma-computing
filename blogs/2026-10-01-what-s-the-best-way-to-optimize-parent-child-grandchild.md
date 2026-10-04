---
title: "What’s the best way to optimize parent→child→grandchild chain to reduce query complexity and improve performance?"
url: "https://community.sigmacomputing.com/t/what-s-the-best-way-to-optimize-parent-child-grandchild-chain-to-reduce-query-complexity-and-improve-performance/7319#post_1"
date: "2026-10-01"
author: "@shahisthak"
feed_url: "https://community.sigmacomputing.com/posts.rss"
---
Context / Model Design My parent (fact) table has multiple rows per issue_number (one row per snapshot). To keep only the latest snapshot per issue, I apply: ROW_NUMBER() OVER (PARTITION BY issue_number ORDER BY snapshot_date DESC) = 1 I then create relationships from this parent fact to dimension tables . In the child table , I “enable” specific dimension columns coming via these relationships because I’m using custom SQL on those columns for filters .
