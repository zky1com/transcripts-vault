---
tags: [organization]
---

# Ryan Deiss

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Ryan Deiss")
SORT publish_date DESC
```
