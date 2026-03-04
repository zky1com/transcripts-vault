---
tags: [organization]
---

# Fund Strap

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Fund Strap")
SORT publish_date DESC
```
