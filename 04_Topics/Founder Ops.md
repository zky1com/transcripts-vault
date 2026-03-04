---
tags: [topic-moc]
---

# Founder Ops

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "founder-ops")
SORT publish_date DESC
```
