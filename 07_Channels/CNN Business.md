---
tags: [channel]
---

# CNN Business

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "CNN Business"
SORT publish_date DESC
```
