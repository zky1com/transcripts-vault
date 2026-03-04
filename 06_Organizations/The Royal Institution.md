---
tags: [organization]
---

# The Royal Institution

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "The Royal Institution")
SORT publish_date DESC
```
