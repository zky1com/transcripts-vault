---
tags: [channel]
---

# All-In Podcast

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "All-In Podcast"
SORT publish_date DESC
```
