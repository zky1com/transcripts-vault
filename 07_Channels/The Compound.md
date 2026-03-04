---
tags: [channel]
---

# The Compound

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "The Compound"
SORT publish_date DESC
```
