---
tags: [topic-moc]
---

# Saas Growth

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "saas-growth")
SORT publish_date DESC
```
