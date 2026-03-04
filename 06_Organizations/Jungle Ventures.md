---
tags: [organization]
---

# Jungle Ventures

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Jungle Ventures")
SORT publish_date DESC
```
