---
tags: [organization]
---

# Business Explains The World

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Business Explains The World")
SORT publish_date DESC
```
