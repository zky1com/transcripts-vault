---
tags: [channel]
---

# Make Things That Matter

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Make Things That Matter"
SORT publish_date DESC
```
