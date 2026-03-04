---
tags: [organization]
---

# Kenji Explains

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Kenji Explains")
SORT publish_date DESC
```
