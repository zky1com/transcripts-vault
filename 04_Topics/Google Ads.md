---
tags: [topic-moc]
---

# Google Ads

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(tags, "google-ads")
SORT publish_date DESC
```
