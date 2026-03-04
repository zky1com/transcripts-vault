---
tags: [organization]
---

# TK Kader

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "TK Kader")
SORT publish_date DESC
```
