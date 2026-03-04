---
tags: [person]
description: "Tom Lee may refer to: Tom Lee (baseball) (1862–1886), baseball player in 1884 Tom Lee (footballer, born 1874) (1874–?), Australian rules footballer for"
---

# Tom Lee

## Description

Tom Lee may refer to: Tom Lee (baseball) (1862–1886), baseball player in 1884 Tom Lee (footballer, born 1874) (1874–?), Australian rules footballer for (Source: Wikipedia search).

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(people_mentioned, "Tom Lee")
SORT publish_date DESC
```

## Claims

```dataview
TABLE file.name as Claim, date
FROM "Claims/Economics"
WHERE speaker = this.file.link
SORT date DESC
```
