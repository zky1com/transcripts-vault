---
tags: [person]
description: "Online profile not confidently resolved yet; this page tracks transcript mentions in the vault."
---

# Ritvik Dashora

## Description

Online profile not confidently resolved yet; this page tracks transcript mentions in the vault. (Source: N/A).

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(people_mentioned, "Ritvik Dashora")
SORT publish_date DESC
```
