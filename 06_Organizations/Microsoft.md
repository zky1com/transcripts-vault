---
tags: [organization]
---

# Microsoft

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Microsoft")
SORT publish_date DESC
```
