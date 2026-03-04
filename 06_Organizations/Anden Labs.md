---
tags: [organization]
---

# Anden Labs

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Anden Labs")
SORT publish_date DESC
```
