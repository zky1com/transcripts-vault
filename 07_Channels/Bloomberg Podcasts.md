---
tags: [channel]
---

# Bloomberg Podcasts

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Bloomberg Podcasts"
SORT publish_date DESC
```
