---
tags: [topic-moc]
---

# Ai Coding

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "ai-coding")
SORT publish_date DESC
```
