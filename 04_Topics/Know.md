---
tags: [topic-moc]
---

# Know

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "know")
SORT publish_date DESC
```
