---
tags: [organization]
---

# This Week in Startups

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "This Week in Startups")
SORT publish_date DESC
```
