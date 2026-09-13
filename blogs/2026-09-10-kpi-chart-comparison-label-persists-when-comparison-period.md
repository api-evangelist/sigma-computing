---
title: "KPI chart — comparison label persists when comparison period has no data"
url: "https://community.sigmacomputing.com/t/kpi-chart-comparison-label-persists-when-comparison-period-has-no-data/7236#post_1"
date: "2026-09-10"
author: "@maijuli"
feed_url: "https://community.sigmacomputing.com/posts.rss"
---
On a KPI chart with a period-over-period comparison configured, when the current period has data but the comparison period has no data (a valid date, just no matching rows), the comparison arrow and % change correctly disappear — but label text remains visible, leaving an orphaned label with no value next to it, and not matching the primary value of the card (the current period’s value). The Format > Comparison > Display label for invalid date field doesn’t address this, since the date itself is valid — there’s just no data for the comparison period. Request: Automatically suppress the compari
