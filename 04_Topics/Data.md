---
tags: [topic-moc]
---

# Data

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "data")
SORT publish_date DESC
```
