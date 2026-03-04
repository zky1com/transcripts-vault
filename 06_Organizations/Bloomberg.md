---
tags: [organization]
---

# Bloomberg

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Bloomberg")
SORT publish_date DESC
```
