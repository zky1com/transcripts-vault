---
tags: [organization]
---

# Sourcery with Molly O'Shea

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Sourcery with Molly O'Shea")
SORT publish_date DESC
```
