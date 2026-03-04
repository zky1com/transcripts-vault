---
tags: [organization]
---

# Excess Returns

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Excess Returns")
SORT publish_date DESC
```
