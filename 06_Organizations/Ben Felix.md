---
tags: [organization]
---

# Ben Felix

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Ben Felix")
SORT publish_date DESC
```
