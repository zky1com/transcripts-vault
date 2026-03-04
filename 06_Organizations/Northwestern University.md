---
tags: [organization]
---

# Northwestern University

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Northwestern University")
SORT publish_date DESC
```
