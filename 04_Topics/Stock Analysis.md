---
tags: [topic-moc]
---

# Stock Analysis

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "stock-analysis")
SORT publish_date DESC
```
