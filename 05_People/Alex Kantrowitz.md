---
tags: [person]
description: "Journalist"
---

# Alex Kantrowitz

## Description

Journalist (Source: Wikidata).

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(people_mentioned, "Alex Kantrowitz")
SORT publish_date DESC
```
