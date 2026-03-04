---
tags: [channel]
---

# The Wall Street Journal

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "The Wall Street Journal"
SORT publish_date DESC
```
