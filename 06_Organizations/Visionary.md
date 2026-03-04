---
tags: [organization]
---

# Visionary

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Visionary")
SORT publish_date DESC
```
