---
tags: [channel]
---

# This Week in Startups

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "This Week in Startups"
SORT publish_date DESC
```
