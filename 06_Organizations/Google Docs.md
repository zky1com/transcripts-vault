---
tags: [organization]
---

# Google Docs

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Google Docs")
SORT publish_date DESC
```
