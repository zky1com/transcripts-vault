---
tags: [organization]
---

# Google Ads

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Google Ads")
SORT publish_date DESC
```
