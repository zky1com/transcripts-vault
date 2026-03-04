---
tags: [person]
description: "Novo Nordisk A/S is a Danish multinational pharmaceutical company headquartered in Bagsværd. Novo Nordisk is controlled by majority shareholder Novo Holdings"
---

# Novo Nordisk

## Description

Novo Nordisk A/S is a Danish multinational pharmaceutical company headquartered in Bagsværd. Novo Nordisk is controlled by majority shareholder Novo Holdings (Source: Wikipedia search).

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(people_mentioned, "Novo Nordisk")
SORT publish_date DESC
```
