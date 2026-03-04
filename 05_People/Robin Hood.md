---
tags: [person]
description: "Robin Hood is a legendary heroic outlaw originally depicted in English folklore and subsequently featured in literature, theatre, and cinema. According"
---

# Robin Hood

## Description

Robin Hood is a legendary heroic outlaw originally depicted in English folklore and subsequently featured in literature, theatre, and cinema. According (Source: Wikipedia search).

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(people_mentioned, "Robin Hood")
SORT publish_date DESC
```
