---
tags: [channel]
---

# Terem

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Terem"
SORT publish_date DESC
```
