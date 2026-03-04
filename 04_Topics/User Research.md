---
tags: [topic-moc]
---

# User Research

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "user-research")
SORT publish_date DESC
```
