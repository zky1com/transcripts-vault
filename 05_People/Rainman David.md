---
tags: [person]
description: "Chicago Film Critics Association Awards Best Actor Dustin Hoffman Nominated David di Donatello Awards Best Foreign Film Barry Levinson Won Best Foreign Director"
---

# Rainman David

## Description

Chicago Film Critics Association Awards Best Actor Dustin Hoffman Nominated David di Donatello Awards Best Foreign Film Barry Levinson Won Best Foreign Director (Source: Wikipedia search).

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(people_mentioned, "Rainman David")
SORT publish_date DESC
```
