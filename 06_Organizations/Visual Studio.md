---
tags: [organization]
---

# Visual Studio

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Visual Studio")
SORT publish_date DESC
```
