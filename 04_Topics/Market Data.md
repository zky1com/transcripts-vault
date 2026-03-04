---
tags: [topic-moc]
---

# Market Data

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "market-data")
SORT publish_date DESC
```
