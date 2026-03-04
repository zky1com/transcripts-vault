---
tags: [topic-moc]
---

# General

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "general")
SORT publish_date DESC
```
