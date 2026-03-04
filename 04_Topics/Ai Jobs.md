---
tags: [topic-moc]
---

# Ai Jobs

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "ai-jobs")
SORT publish_date DESC
```
