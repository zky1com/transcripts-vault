---
tags: [organization]
---

# Nick Colas and Jessica Rabe of DataTrek Research

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Nick Colas and Jessica Rabe of DataTrek Research")
SORT publish_date DESC
```
