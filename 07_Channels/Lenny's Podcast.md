---
tags: [channel]
---

# Lenny's Podcast

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Lenny's Podcast"
SORT publish_date DESC
```
