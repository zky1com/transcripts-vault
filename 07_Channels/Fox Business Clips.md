---
tags: [channel]
---

# Fox Business Clips

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Fox Business Clips"
SORT publish_date DESC
```
