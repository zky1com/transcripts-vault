---
tags: [organization]
---

# Bloomberg Audio Studios

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Bloomberg Audio Studios")
SORT publish_date DESC
```
