---
tags: [organization]
---

# World Academic Forum

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "World Academic Forum")
SORT publish_date DESC
```
