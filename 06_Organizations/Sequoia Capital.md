---
tags: [organization]
---

# Sequoia Capital

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Sequoia Capital")
SORT publish_date DESC
```
