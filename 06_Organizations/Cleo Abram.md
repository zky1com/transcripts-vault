---
tags: [organization]
---

# Cleo Abram

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Cleo Abram")
SORT publish_date DESC
```
