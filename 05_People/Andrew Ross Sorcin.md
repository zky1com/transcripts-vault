---
tags: [person]
description: "Online profile not confidently resolved yet; this page tracks transcript mentions in the vault."
---

# Andrew Ross Sorcin

## Description

Online profile not confidently resolved yet; this page tracks transcript mentions in the vault. (Source: N/A).

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(people_mentioned, "Andrew Ross Sorcin")
SORT publish_date DESC
```
