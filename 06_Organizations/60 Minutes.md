---
tags: [organization]
---

# 60 Minutes

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "60 Minutes")
SORT publish_date DESC
```
