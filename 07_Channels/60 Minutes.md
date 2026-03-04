---
tags: [channel]
---

# 60 Minutes

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "60 Minutes"
SORT publish_date DESC
```
