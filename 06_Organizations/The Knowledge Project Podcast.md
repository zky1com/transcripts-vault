---
tags: [organization]
---

# The Knowledge Project Podcast

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "The Knowledge Project Podcast")
SORT publish_date DESC
```
