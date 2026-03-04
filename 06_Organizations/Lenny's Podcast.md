---
tags: [organization]
---

# Lenny's Podcast

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Lenny's Podcast")
SORT publish_date DESC
```
