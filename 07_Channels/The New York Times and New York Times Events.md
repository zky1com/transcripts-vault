---
tags: [channel]
---

# The New York Times and New York Times Events

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "The New York Times and New York Times Events"
SORT publish_date DESC
```
