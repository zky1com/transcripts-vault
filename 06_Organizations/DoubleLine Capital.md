---
tags: [organization]
---

# DoubleLine Capital

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "DoubleLine Capital")
SORT publish_date DESC
```
