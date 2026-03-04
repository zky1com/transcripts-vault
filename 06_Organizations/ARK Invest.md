---
tags: [organization]
---

# ARK Invest

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "ARK Invest")
SORT publish_date DESC
```
