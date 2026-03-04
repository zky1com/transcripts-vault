---
tags: [organization]
---

# Dividendology

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Dividendology")
SORT publish_date DESC
```
