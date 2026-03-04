---
tags: [organization]
---

# Bloomberg Television

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Bloomberg Television")
SORT publish_date DESC
```
