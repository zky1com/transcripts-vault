---
tags: [topic-moc]
---

# Sales Process

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "sales-process")
SORT publish_date DESC
```
