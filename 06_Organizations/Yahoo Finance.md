---
tags: [organization]
---

# Yahoo Finance

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Yahoo Finance")
SORT publish_date DESC
```
