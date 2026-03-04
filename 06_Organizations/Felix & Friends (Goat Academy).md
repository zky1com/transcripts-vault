---
tags: [organization]
---

# Felix & Friends (Goat Academy)

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Felix & Friends (Goat Academy)")
SORT publish_date DESC
```
