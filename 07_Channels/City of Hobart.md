---
tags: [channel]
---

# City of Hobart

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "City of Hobart"
SORT publish_date DESC
```
