---
tags: [organization]
---

# Data Studio

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Data Studio")
SORT publish_date DESC
```
