---
tags: [organization]
---

# Modest Money

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Modest Money")
SORT publish_date DESC
```
