---
tags: [organization]
---

# StrategyQuant

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "StrategyQuant")
SORT publish_date DESC
```
