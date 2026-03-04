---
tags: [organization]
---

# Making Money

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Making Money")
SORT publish_date DESC
```
