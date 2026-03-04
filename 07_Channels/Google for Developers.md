---
tags: [channel]
---

# Google for Developers

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Google for Developers"
SORT publish_date DESC
```
