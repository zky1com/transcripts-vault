---
tags: [organization]
---

# Dumb Money Live

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Dumb Money Live")
SORT publish_date DESC
```
