---
tags: [topic-moc]
---

# Risk Compliance

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "risk-compliance")
SORT publish_date DESC
```
