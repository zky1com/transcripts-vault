---
tags: [organization]
---

# Google Deep Mind

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Google Deep Mind")
SORT publish_date DESC
```
