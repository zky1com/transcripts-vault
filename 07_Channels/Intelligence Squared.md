---
tags: [channel]
---

# Intelligence Squared

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Intelligence Squared"
SORT publish_date DESC
```
