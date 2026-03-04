---
tags: [channel]
---

# ProductDock

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "ProductDock"
SORT publish_date DESC
```
