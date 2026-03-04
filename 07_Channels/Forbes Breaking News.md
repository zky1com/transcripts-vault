---
tags: [channel]
---

# Forbes Breaking News

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Forbes Breaking News"
SORT publish_date DESC
```
