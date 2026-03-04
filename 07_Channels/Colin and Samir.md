---
tags: [channel]
---

# Colin and Samir

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Colin and Samir"
SORT publish_date DESC
```
