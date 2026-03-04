---
tags: [organization]
---

# Bloomberg Business App

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Bloomberg Business App")
SORT publish_date DESC
```
