---
tags: [topic-moc]
---

# Youtube

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "youtube")
SORT publish_date DESC
```
