---
tags: [channel]
---

# Dumb Money Live

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Dumb Money Live"
SORT publish_date DESC
```
