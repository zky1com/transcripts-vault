---
tags: [organization]
---

# Google Cloud

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Google Cloud")
SORT publish_date DESC
```
