---
tags: [topic-moc]
---

# Product Discovery

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "product-discovery")
SORT publish_date DESC
```
