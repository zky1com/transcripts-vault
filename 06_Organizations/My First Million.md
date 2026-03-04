---
tags: [organization]
---

# My First Million

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "My First Million")
SORT publish_date DESC
```
