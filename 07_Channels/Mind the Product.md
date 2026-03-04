---
tags: [channel]
---

# Mind the Product

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Mind the Product"
SORT publish_date DESC
```
