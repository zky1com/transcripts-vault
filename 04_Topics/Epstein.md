---
tags: [topic-moc]
---

# Epstein

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "epstein")
SORT publish_date DESC
```
