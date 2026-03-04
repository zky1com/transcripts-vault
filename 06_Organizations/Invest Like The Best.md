---
tags: [organization]
---

# Invest Like The Best

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Invest Like The Best")
SORT publish_date DESC
```
