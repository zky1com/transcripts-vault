---
tags: [channel]
---

# Weaviate vector database

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Weaviate vector database"
SORT publish_date DESC
```
