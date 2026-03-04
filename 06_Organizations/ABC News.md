---
tags: [organization]
---

# ABC News

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "ABC News")
SORT publish_date DESC
```
