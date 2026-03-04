---
tags: [organization]
---

# Charles Schwab

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Charles Schwab")
SORT publish_date DESC
```
