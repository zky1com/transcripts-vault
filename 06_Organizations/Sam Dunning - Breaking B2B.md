---
tags: [organization]
---

# Sam Dunning - Breaking B2B

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Sam Dunning - Breaking B2B")
SORT publish_date DESC
```
