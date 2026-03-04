---
tags: [organization]
---

# World Economic Forum

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "World Economic Forum")
SORT publish_date DESC
```
