---
tags: [organization]
---

# Elon Musk Editor

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Elon Musk Editor")
SORT publish_date DESC
```
