---
tags: [topic-moc]
---

# Court

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "court")
SORT publish_date DESC
```
