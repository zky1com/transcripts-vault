---
tags: [organization]
---

# The Startup Podcast

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "The Startup Podcast")
SORT publish_date DESC
```
