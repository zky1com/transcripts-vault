---
tags: [organization]
---

# Looker Studio

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Looker Studio")
SORT publish_date DESC
```
