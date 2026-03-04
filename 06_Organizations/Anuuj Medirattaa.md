---
tags: [organization]
---

# Anuuj Medirattaa

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Anuuj Medirattaa")
SORT publish_date DESC
```
