---
tags: [topic-moc]
---

# Pricing

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "pricing")
SORT publish_date DESC
```
