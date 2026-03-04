---
tags: [topic-moc]
---

# Saas Gtm

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "saas-gtm")
SORT publish_date DESC
```
