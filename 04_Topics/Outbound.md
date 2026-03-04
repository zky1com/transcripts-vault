---
tags: [topic-moc]
---

# Outbound

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "outbound")
SORT publish_date DESC
```
