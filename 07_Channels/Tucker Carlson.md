---
tags: [channel]
---

# Tucker Carlson

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Tucker Carlson"
SORT publish_date DESC
```
