---
tags: [channel]
---

# Sourcery with Molly O'Shea

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Sourcery with Molly O'Shea"
SORT publish_date DESC
```
