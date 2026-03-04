---
tags: [topic-moc]
---

# Product Strategy

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "product-strategy")
SORT publish_date DESC
```
