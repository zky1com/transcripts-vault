---
tags: [topic-moc]
---

# Valuation

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "valuation")
SORT publish_date DESC
```
