---
tags: [channel]
---

# Financial Times

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Financial Times"
SORT publish_date DESC
```
