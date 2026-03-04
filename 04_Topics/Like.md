---
tags: [topic-moc]
---

# Like

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "like")
SORT publish_date DESC
```
