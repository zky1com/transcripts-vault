---
tags: [channel]
---

# Yahoo Finance

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Yahoo Finance"
SORT publish_date DESC
```
