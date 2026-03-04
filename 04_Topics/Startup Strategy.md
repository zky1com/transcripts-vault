---
tags: [topic-moc]
---

# Startup Strategy

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "startup-strategy")
SORT publish_date DESC
```
