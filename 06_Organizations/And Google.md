---
tags: [organization]
---

# And Google

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "And Google")
SORT publish_date DESC
```
