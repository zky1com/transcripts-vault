---
tags: [channel]
---

# Lex Fridman

```dataview
TABLE title as "Title", publish_date as "Date", duration as "Duration", content_type as "Type"
FROM "Videos"
WHERE channel = "Lex Fridman"
SORT publish_date DESC
```
