---
tags: [topic-moc]
---

# Developer Productivity

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "developer-productivity")
SORT publish_date DESC
```
