---
tags: [organization]
---

# Dan Martell

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Dan Martell")
SORT publish_date DESC
```
