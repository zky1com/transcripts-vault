---
tags: [organization]
---

# Logically Answered

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Logically Answered")
SORT publish_date DESC
```
