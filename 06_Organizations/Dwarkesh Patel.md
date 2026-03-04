---
tags: [organization]
---

# Dwarkesh Patel

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Dwarkesh Patel")
SORT publish_date DESC
```
