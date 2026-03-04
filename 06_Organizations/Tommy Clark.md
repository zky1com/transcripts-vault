---
tags: [organization]
---

# Tommy Clark

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Tommy Clark")
SORT publish_date DESC
```
