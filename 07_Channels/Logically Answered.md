---
tags: [channel]
---

# Logically Answered

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Logically Answered"
SORT publish_date DESC
```
