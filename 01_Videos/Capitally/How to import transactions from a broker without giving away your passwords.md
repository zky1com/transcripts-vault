---
title: "How to import transactions from a broker without giving away your passwords"
people_mentioned: ["Interactive Brokers"]
channel: "Capitally"
video_id: "0MkQUM9DV50"
url: "https://www.youtube.com/watch?v=0MkQUM9DV50"
publish_date: 2025-03-04
duration: "5:33"
word_count: 890
content_type: "tutorial"
delivery_mode: "technique"
broad_category: "finance-investing"
subcategories: ["portfolio-management", "stock-analysis"]
series_name: ""
episode_id: ""
primary_person: "Interactive Brokers"
host_names: []
interviewer_names: []
interviewee_profiles: []
speaker_profiles: ["Interactive Brokers"]
organizations_mentioned: ["Capitally"]
locations_mentioned: []
tools_mentioned: []
companies_mentioned: []
topics: ["portfolio-management", "stock-analysis", "import"]
tags: ["portfolio-management", "stock-analysis", "import"]
pipeline_stage: video_only
claims_status: pending
evidence_status: pending
claims_count: 0
evidence_count: 0
batch_id: ""
last_processed_at: "2026-03-03"
speech_status: pending
world_status: pending
speech_evidence_count: 0
world_evidence_count: 0
---


## Summary

The discussion centers on import, transactions, want. When you import a file for the first time, you will see this screen. You now know how to import your transactions, handle any issues that pop up, and make sure everything is correct. If you want to go back to what was originally found, just click this button and it will reset to 6 Swiss.

## Key Insights


- Do you want to track your investments across multiple brokers, but don't want to share your login credentials with third party apps or spend hours scoping data into spreadsheets?

- Since we are doing a fresh import, the numbers match exactly, but if you are adding new transactions later, this will show you only the difference.

- You now know how to import your transactions, handle any issues that pop up, and make sure everything is correct.

- By default, we create an account with the same name as the broker, but you can choose any existing account, or even create a new one by clicking right here.

- I will show you how to securely import your trading history into Capitally using just your broker statements now, giving away your passwords.

- When you import a file for the first time, you will see this screen.




## Key Quotes


> Do you want to track your investments across multiple brokers, but don't want to share your login credentials with third party apps or spend hours scoping data into spreadsheets?


> I will show you how to securely import your trading history into Capitally using just your broker statements now, giving away your passwords.


> No manual entry headaches, just a simple, private way to see all your investments in one place.


> To get started, open the import section and you will see a list of brokers to choose from.






## Full Transcript

<details>
<summary>Click to expand full transcript (890 words)</summary>

Do you want to track your investments
across multiple brokers, but don't want to share your login credentials
with third party apps or spend hours scoping data into spreadsheets? I will show you how to securely import
your trading history into Capitally using just your broker statements
now, giving away your passwords. No manual entry headaches, just
a simple, private way to see all your investments in one place. To get started, open the import
section and you will see a list of brokers to choose from. Don't see your broker on the list? No problem, just send a sample
file and we'll add it for you. I'm going to show you how to do
this with interactive brokers. are detailed instructions
on how to export your data. The instructions here look pretty long,
but you only need to most of it once. And then it's smooth sailing from there. I already have a file ready, so
let me show you what happens. When you import a file for the first
time, you will see this screen. Look at these tabs. The input tab shows exactly what is
in your CSV file from the broker. And these other tabs show the
transactions that will be created in Capitally, plus the accounts. In the side panel, you will see some
notes, which you want to review, probably. In this case, it tells me how my
ADR will be imported, and that cash transactions are not imported yet. This is coming in future versions. One really important thing to decide is
where you want these transactions to go. By default, we create an account with
the same name as the broker, but you can choose any existing account, or even
create a new one by clicking right here. I give it a name, pick an icon if
I want, and add it, just like that. Next, we need to make sure the assets we
found match your transactions correctly. Are they on the right exchanges? Are the symbols correct? They are all listed here. If you want to change it, just
click on any name and you can select a different exchange if needed. For example, I want to use the symbol
from Amsterdam instead of 6 Swiss. You can also search for specific
symbols or company name and just pick them from the list. If you want to go back to what was
originally found, just click this button and it will reset to 6 Swiss. Ok, let's click next. Now we are looking at
the summary of balances. This is where you can verify everything. Check if you have the same
amounts of assets as shown in your Interactive Brokers account. See these green numbers below? They show what is being
added in this import. Since we are doing a fresh import, the
numbers match exactly, but if you are adding new transactions later, this
will show you only the difference. The main thing is to verify the
current balance, but you also see how many dividends or fees are
included in the import as well. Okay, let's click import and there we go! It's all in our project now. But wait, let me show you another
scenario another file here. It's similar, but has a few
problems we should talk about. First, notice this warning
about unsupported transactions. If I click on it, I will see the specific
line in the export that won't be imported. Usually, you can actually just ignore But
if you think it actually should be imported, just let us know. Look at this, we've got
a no asset found message. I know this is Merck, so I can
just search for it right here. There it is. Click it, and it's fixed. Okay, all seems fine,
so I can click next now. Now we've got these negative
balance detected errors. This usually means we are missing
some opening transactions, so we are trying to sell more than we own. So let's go back and take a look. The asset was here in BNB, so I sort
the colon by the asset and look for it. Ah, see the transfer? This is causing the issue, and even there
is a note in the side panel about it. These are just internal, interactive
broker transfers, so we can select them all by first sorting the table by
transaction type, And ignore them all. The system also spotted some duplicate transactions from our earlier import. You can update them if needed, but no
duplicates will be created otherwise. One last thing. Sometimes, you might pick
the wrong file by accident. If you do, you will see this
error message saying it can't load the data for various reasons. Most of the time this just means
you need to check if you've exported the data correctly and
you are loading the correct file. If you did everything properly,
then maybe we don't yet support your language, transaction types,
or broker changed their format. In any case, please send us a sample
file and we'll add proper support for it. And if you feel adventurous, you can
even try editing the preset yourself. And that's it! You now know how to import your
transactions, handle any issues that pop up, and make sure everything is correct. Thanks for watching!

</details>
