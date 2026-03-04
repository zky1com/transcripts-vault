---
tags: [organization]
---

# The Compound

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "The Compound")
SORT publish_date DESC
```
