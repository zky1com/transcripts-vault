---
tags: [organization]
---

# Sander Recommends

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Sander Recommends")
SORT publish_date DESC
```
