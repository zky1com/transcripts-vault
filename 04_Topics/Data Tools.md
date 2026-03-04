---
tags: [topic-moc]
---

# Data Tools

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "data-tools")
SORT publish_date DESC
```
