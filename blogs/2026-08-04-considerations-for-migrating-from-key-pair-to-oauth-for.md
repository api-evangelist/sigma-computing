---
title: "Considerations for migrating from Key-pair to OAuth for input tables and write-back"
url: "https://community.sigmacomputing.com/t/considerations-for-migrating-from-key-pair-to-oauth-for-input-tables-and-write-back/7167#post_1"
date: "2026-08-04"
author: "@ratnashiv Ratna"
feed_url: "https://community.sigmacomputing.com/posts.rss"
---
Sigma Account Type: Admin Connection : Snowflake Table of Contents How Key-pair access works Considerations: Write-back moves from a shared identity model to per-user authorization Validate schema-level write privileges before you migrate Existing input table objects do not automatically realign to new OAuth roles Troubleshooting after migration usually comes down to SIGDS versus WAL access Service-account planning matters for write-back reliability Use dedicated write-back schemas and leave Sigma-managed objects alone Sources If your Snowflake connection in Sigma currently uses Key-pair authe
