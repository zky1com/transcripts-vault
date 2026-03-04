---
tags: [person]
description: "Archaeologist in Australia"
---

# Mike Green

## Description

Archaeologist in Australia (Source: Wikidata).

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(people_mentioned, "Mike Green")
SORT publish_date DESC
```
