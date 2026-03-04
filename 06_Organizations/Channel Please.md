---
tags: [organization]
---

# Channel Please

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Channel Please")
SORT publish_date DESC
```
