---
tags: [organization]
---

# Modest Money Channel

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Modest Money Channel")
SORT publish_date DESC
```
