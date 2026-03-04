---
tags: [organization]
---

# Sparkline Capital

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Sparkline Capital")
SORT publish_date DESC
```
