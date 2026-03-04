---
tags: [organization]
---

# Google Gemini

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "Google Gemini")
SORT publish_date DESC
```
