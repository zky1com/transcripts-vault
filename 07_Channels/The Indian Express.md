---
tags: [channel]
---

# The Indian Express

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "The Indian Express"
SORT publish_date DESC
```
