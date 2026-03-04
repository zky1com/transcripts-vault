---
tags: [organization]
---

# Risk Reversal Podcast

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Risk Reversal Podcast")
SORT publish_date DESC
```
