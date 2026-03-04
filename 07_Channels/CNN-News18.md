---
tags: [channel]
---

# CNN-News18

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "CNN-News18"
SORT publish_date DESC
```
