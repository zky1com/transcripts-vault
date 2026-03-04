---
tags: [organization]
---

# Google Play

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Google Play")
SORT publish_date DESC
```
