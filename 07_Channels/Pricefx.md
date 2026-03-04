---
tags: [channel]
---

# Pricefx

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Pricefx"
SORT publish_date DESC
```
