---
tags: [organization]
---

# Creative Planning

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Creative Planning")
SORT publish_date DESC
```
