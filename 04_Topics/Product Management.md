---
tags: [topic-moc]
---

# Product Management

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "product-management")
SORT publish_date DESC
```
