---
tags: [topic-moc]
---

# Api Integration

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "api-integration")
SORT publish_date DESC
```
