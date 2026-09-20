# Find and review your recurring spending

Bank statements show where money went, but it can take some work to understand what keeps coming back. Payment references change, bills follow different schedules, and a PayPal debit may not tell you who you paid.

These instructions ask an AI agent to build a tool for reviewing your recurring spending. It brings your records together, looks for patterns and investigates unfamiliar merchants. You can search the results, inspect payment histories, add notes and mark what you have reviewed.

## What you need

1. A paid AI subscription with enough usage for a substantial task. Allow time for the agent to process your records, build the app and check it. You may need several sessions to finish.
2. An agent mode that can work with files, run code and research the web. Give it access to your working folder and permission to create and update files and run code there.
3. Use the best model available to you, with a high thinking or reasoning setting where available. The agent needs to investigate ambiguous records as well as build the tool.

## Privacy and your financial data

Assume some of your transaction data will go to your AI provider. That can include merchant names, dates, amounts and statement extracts. Keeping the files on your computer does not mean the agent's work happens entirely there.

The prompt asks for an app that runs locally, without external analytics or unnecessary third-party requests. Only supply financial records you are comfortable sharing with your chosen AI provider.

## Prepare your files

Create a working folder and put your exports in a `statements` subfolder:

- Bank and credit card statements from the accounts you want to review. CSV exports are easiest to work with;
- Payment and purchase histories from services such as PayPal and Apple, if available. These can explain who or what a bank payment was for.
- Relevant receipts or subscription records that could help explain unclear payments.

Include at least a year if you can. Around two years gives the agent a better chance of finding annual renewals. Shorter histories are still useful.

Give accounts clear labels and mention any known gaps. Keep dates, amounts, currencies and payment references intact. You do not need to clean up or combine the exports first.

## Getting started

Copy the [full agent instructions](prompt.md) into your agent and give it access to the working folder. It will inspect the records, choose an implementation for your computer and build the review. The prompt tells it to preserve your original files.

The result will be a locally running app. The agent will give you a link to open it in your browser, with instructions for starting it again later. The prompt asks it to keep the app accessible only on your computer.

Work through the results and correct anything it has misunderstood. A regular purchase is not necessarily a subscription. You decide which payments to keep, investigate or cancel yourself.

## Adding more statements

Add the new files and ask the agent to update the review, preserve your notes and highlight what changed. Reopening the page alone does not update the analysis. Keep a backup of the whole working folder.
