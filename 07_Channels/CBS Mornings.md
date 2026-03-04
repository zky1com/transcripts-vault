---
tags: [channel]
---

# CBS Mornings

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "CBS Mornings"
SORT publish_date DESC
```
