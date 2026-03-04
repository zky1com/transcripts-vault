---
tags: [organization]
---

# The Independent

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "The Independent")
SORT publish_date DESC
```
