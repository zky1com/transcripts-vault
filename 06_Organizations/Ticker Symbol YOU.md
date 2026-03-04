---
tags: [organization]
---

# Ticker Symbol: YOU

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Ticker Symbol: YOU")
SORT publish_date DESC
```
