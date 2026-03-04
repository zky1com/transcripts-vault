---
tags: [organization]
---

# Alex Kantrowitz

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Alex Kantrowitz")
SORT publish_date DESC
```
