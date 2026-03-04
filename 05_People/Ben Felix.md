---
tags: [person]
description: "Participant in the Las Vegas Gay, Lesbian, Bisexual and Transgender Archives Oral History Project at the University of Nevada, Las Vegas"
---

# Ben Felix

## Description

Participant in the Las Vegas Gay, Lesbian, Bisexual and Transgender Archives Oral History Project at the University of Nevada, Las Vegas (Source: Wikidata).

```dataview
TABLE title as "Title", channel as "Channel", publish_date as "Date"
FROM "Videos"
WHERE contains(people_mentioned, "Ben Felix")
SORT publish_date DESC
```

## Claims

```dataview
TABLE file.name as Claim, date
FROM "Claims/Economics"
WHERE speaker = this.file.link
SORT date DESC
```
