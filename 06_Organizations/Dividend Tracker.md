---
tags: [organization]
---

# Dividend Tracker

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Dividend Tracker")
SORT publish_date DESC
```
