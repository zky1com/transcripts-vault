---
tags: [organization]
---

# Google Chrome

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Google Chrome")
SORT publish_date DESC
```
