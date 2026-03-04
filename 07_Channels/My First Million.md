---
tags: [channel]
---

# My First Million

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "My First Million"
SORT publish_date DESC
```
