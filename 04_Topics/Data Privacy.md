---
tags: [topic-moc]
---

# Data Privacy

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "data-privacy")
SORT publish_date DESC
```
