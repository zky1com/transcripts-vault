---
tags: [topic-moc]
---

# Automation

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "automation")
SORT publish_date DESC
```
