---
tags: [channel]
---

# Bloomberg Originals

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Bloomberg Originals"
SORT publish_date DESC
```
