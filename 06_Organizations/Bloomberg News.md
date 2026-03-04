---
tags: [organization]
---

# Bloomberg News

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Bloomberg News")
SORT publish_date DESC
```
