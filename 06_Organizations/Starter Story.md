---
tags: [organization]
---

# Starter Story

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Starter Story")
SORT publish_date DESC
```
