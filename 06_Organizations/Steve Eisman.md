---
tags: [organization]
---

# Steve Eisman

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Steve Eisman")
SORT publish_date DESC
```
