---
tags: [organization]
---

# Fox News

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Fox News")
SORT publish_date DESC
```
