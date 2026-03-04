---
tags: [organization]
---

# Saas Marketing Wizards

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Saas Marketing Wizards")
SORT publish_date DESC
```
