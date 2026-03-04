---
tags: [organization]
---

# Rob Walling

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Rob Walling")
SORT publish_date DESC
```
