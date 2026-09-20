---
title: "Optimizing for Alpha Query: this one trick you should know to \"hide\" your parent table"
url: "https://community.sigmacomputing.com/t/optimizing-for-alpha-query-this-one-trick-you-should-know-to-hide-your-parent-table/3959#post_2"
date: "2026-09-14"
author: "@nathan Nathan Parrish"
feed_url: "https://community.sigmacomputing.com/posts.rss"
---
This technique is generally no longer necessary in light of the ability to Configure data loading to specifically force data prefetch. However, to prepopulate filter value lists you may still want to use this trick. But note that we no longer automatically load the values of a table which is not displaying rows.
