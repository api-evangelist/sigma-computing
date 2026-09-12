---
title: "Fixing The \"Click Tax\": Replace references, smart groupings, and multi-column bulk actions"
url: "https://community.sigmacomputing.com/t/fixing-the-click-tax-replace-references-smart-groupings-and-multi-column-bulk-actions/6989#post_4"
date: "2026-09-04"
author: "@willchamp William Brown"
feed_url: "https://community.sigmacomputing.com/posts.rss"
---
I love all these ideas and have a lot of thoughts on the second one in particular. I understand concatenating the function and existing column name as it helps differentiate a column in your current element from a parent element’s untransformed column, but when we’re utilizing a hygienic text function like Trim or Replace on a column we’re pulling directly from the parent , it would be nice if it would inherit the existing name. Perhaps a workbook configuration setting like “inherit parent names” (or something better, naming a feature is not my strong suit!) would be good.
