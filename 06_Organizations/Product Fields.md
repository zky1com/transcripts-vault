---
tags: [organization]
---

# Product Fields

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Product Fields")
SORT publish_date DESC
```
