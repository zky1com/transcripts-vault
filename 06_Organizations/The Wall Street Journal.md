---
tags: [organization]
---

# The Wall Street Journal

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "The Wall Street Journal")
SORT publish_date DESC
```
