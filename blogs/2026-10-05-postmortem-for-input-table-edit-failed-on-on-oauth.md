---
title: "Postmortem for Input table edit failed on on OAuth connections migrated from non-OAuth"
url: "https://community.sigmacomputing.com/t/postmortem-for-input-table-edit-failed-on-on-oauth-connections-migrated-from-non-oauth/7332#post_1"
date: "2026-10-05"
author: "@betty Betty"
feed_url: "https://community.sigmacomputing.com/posts.rss"
---
RCA - Input table edit failed on on OAuth connections migrated from non-OAuth Incident Start Time: 2026-09-10 11:41 UTC Incident End Time: 2026-09-12 00:16 Summary Input tables and materializations on connections moved from non-OAuth to OAuth failed with write-back errors. Input tables and materializations created after the migration were not affected. Timeline Time (UTC) Event 2026-07-27 A product update to OAuth connection editing is deployed, after which customers who move from non-OAuth to OAuth warehouse connections would experience materialization and IT edit failures.
