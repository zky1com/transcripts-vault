---
tags: [organization]
---

# 20VC with Harry Stebbings

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(organizations_mentioned, "20VC with Harry Stebbings")
SORT publish_date DESC
```
