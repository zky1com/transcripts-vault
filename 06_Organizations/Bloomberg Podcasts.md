---
tags: [organization]
---

# Bloomberg Podcasts

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Bloomberg Podcasts")
SORT publish_date DESC
```
