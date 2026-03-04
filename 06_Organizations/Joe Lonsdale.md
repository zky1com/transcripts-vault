---
tags: [organization]
---

# Joe Lonsdale

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Joe Lonsdale")
SORT publish_date DESC
```
