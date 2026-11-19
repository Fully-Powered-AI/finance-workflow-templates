# Supplier bill review and payment-run preparation

Check every supplier bill against its purchase order and receipts, stop duplicates and changed bank details, and propose a run. A person approves.

> [!TIP]
> **Missing a template that is not listed here, or want these customized for your organization? Reach out to us.** This is a template, made to be customized and deployed. FullyPowered AI customizes and builds AI workflows, connects them to your business systems, installs them in your agents and puts them in the hands of the people who own the work. [See Supplier bill review and payment-run preparation on our website](https://fullypowered.ai/workflows/supplier-bill-review-and-payment-run-preparation/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run). Not sure where to start? Email hello@fullypowered.ai and a person will answer.

**Quick start**

1. Read EXAMPLE.md to see what a good result looks like.
2. Copy all of TEMPLATE.md into your assistant, then give it your own inputs, or the sample ones from EXAMPLE.md.
3. Read what comes back. It marks what it checked and what is left for you.

*Workflow template · Finance and accounting · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/supplier-bill-review-and-payment-run-preparation/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run)*

## The outcome

The approver signs off a payment run in minutes and knows exactly what they are signing. Every bill on the sheet has been checked against what was ordered and what arrived. Every bill left off the sheet is named, with the reason, the amount in question and the person who can clear it.

The expensive mistakes are caught before the money moves: the bill paid twice, the short delivery billed in full, the price that crept above the order, the bill announcing a new bank account. A supplier holding a credit is shown with what is owed, the credit and the difference, so the approver sees the credit before paying the bill in full.

The workflow template prepares and checks. A person approves the run, and a person makes the payments.

## Who starts the work, and when

The payables clerk or bookkeeper starts it before each payment run, weekly or fortnightly, once the latest bills are entered and the receiving log is up to date. In a small company the owner runs it themselves.

The owner or finance lead approves the run. The buyer answers price questions, whoever receives goods answers quantity questions, and the person with bank access pays what was approved.

## What they supply

- **The open bills,** exported from the accounting system or kept on a spreadsheet, with each bill’s lines.
- **The purchase orders** those bills refer to.
- **The receiving log:** what arrived, when, against which order.
- **The supplier list,** with terms and the last four digits of the pay-to account on file.
- **Bills paid in the last 90 days,** for the duplicate check.
- **Your settings:** the run date, the tolerances, when an order is required, and the cash position if you want it on the sheet.

No connection to your bank or accounting system is needed, and none is asked for.

## What comes out

One payment-run sheet, in a fixed order:

1.  **The picture.** How many bills, how much, how many are in the run, held, stopped or not yet due.
2.  **Stopped.** Any bill whose bank details differ from the ones on file, with the phone check that clears it.
3.  **Held.** Each bill that failed a check, with what was billed, what it was checked against, the gap in dollars and who answers.
4.  **Passed with a note.** Bills that passed with a small price difference inside the tolerance, or a regular bill that moved from the last one.
5.  **Credits.** Each supplier holding a credit: owed, credit and net.
6.  **The proposed run.** Overdue bills first, then early-payment discounts that would lapse before the next run, then what falls due inside the window, with the total. The bills that passed and are not yet due are listed after it.
7.  **The tie-out and the cash line.** In the run plus held plus stopped plus not yet due equals the open bills total, with credit notes counted apart.
8.  **Decisions and questions.** What the approver must decide, and what to ask the buyer, the warehouse and each supplier, followed by the held and stopped bills that will be overdue before the next run if nobody clears them.

Good looks like this: the approver can trace any figure to a row in an export, and every bill outside the run still appears on the sheet with its reason.

See the worked example in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Finance and accounting](https://fullypowered.ai/functions/finance-and-accounting/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run), which owns payables and the payment run.
- [Procurement and suppliers](https://fullypowered.ai/functions/procurement-and-suppliers/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run), whose orders and agreed prices are what each bill is checked against.
- [Manufacturing](https://fullypowered.ai/industries/manufacturing/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run), where materials are billed by the line and short deliveries are routine.
- [Construction](https://fullypowered.ai/industries/construction/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run), where one supplier bill can cover several deliveries to several sites.
- [E-commerce and retail](https://fullypowered.ai/industries/ecommerce-and-retail/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run), where stock arrives in part shipments and the bill arrives whole.
- [Hospitality](https://fullypowered.ai/industries/hospitality/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run), where many small supplier bills arrive every week and prices move often.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run), where the run has always depended on one careful person and should not.

## What has to change for your company

- **Your tolerances.** How far a billed price may sit above the order before someone looks, and whether any quantity difference is allowed.
- **Your order rule.** Which bills need a purchase order, and which never do, such as utilities and rent.
- **Your run rhythm.** The run day, and how far ahead a run looks.
- **Your roles.** Who approves, who pays, who answers for price and for receiving, and who phones a supplier about a bank change.
- **Your exports.** The column names your accounting system produces, so the template reads them as they come.
- **Your platform.** It runs in ChatGPT, Claude, Copilot or Gemini. Decide which exports the assistant may read.

## What has been checked

FullyPowered AI wrote this workflow template. It was editorially reviewed on 9 November 2026. It was tried on its own example in one AI product on 9 November 2026, revised and tried again the same day; the record of the second run is published with the template, and lists the edits made afterward that have not been run again. That is a trial, not a test. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on past payment runs your bookkeeper already knows, with hard cases written in advance: a bill entered twice, a short delivery, a price above the order, a changed bank account, a supplier with a credit. The approver checks every figure against the exports before anyone relies on the sheet. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run) sets those cases up, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run) describes the record we keep.

- Written by FullyPowered AI.
- Sources and rights reviewed.
- Editorially reviewed on 9 November 2026.
- Package format checked by script on every release.
- Tried once on its example in Claude on 9 November 2026. The record is in [TRIAL.md](TRIAL.md).
- Not yet tested in a client environment.

## What is in this folder

- [TEMPLATE.md](TEMPLATE.md): the complete workflow template. Roles, inputs, the procedure, exceptions and stop conditions, the output format, a reviewer checklist, acceptance tests, the instructions for an AI assistant and what to customize.
- [EXAMPLE.md](EXAMPLE.md): a worked example.
- [TRIAL.md](TRIAL.md): what came out when the template was tried on its example.
- [SKILL.md](SKILL.md): the technical file, for AI products that load packaged instructions from a folder.
- [SOURCES.md](SOURCES.md): what the workflow template drew on, with licences.
- [LICENSE](LICENSE): MIT. Use it, change it, make it yours.

## Start using it

1. Read [EXAMPLE.md](EXAMPLE.md) to see what a good result looks like.
2. Open [TEMPLATE.md](TEMPLATE.md) and set every item under "What to customize" to your own rules, roles and limits.
3. Give your AI assistant the instruction block and the output format from the template, with your own limits in place of the ones the instructions leave open in square brackets. Paste them in as custom instructions in ChatGPT, Claude, Copilot or Gemini, or copy this whole folder into a product that loads `SKILL.md` packages. This folder stands alone; you do not need the rest of the repository.
4. Run it on past work first, using the reviewer checklist and acceptance tests in the template, before anyone relies on it.

## Related workflow templates

- [Receivables exception review](../receivables-exception-review/)
- [Weekly receivables summary](../weekly-receivables-summary/)
- [SOP exception capture](https://fullypowered.ai/workflows/sop-exception-capture/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run)

## Make it yours

This workflow template is an example and a starting point. FullyPowered AI adapts it to how your company works, proves it on real work and rolls it out to the roles that use it. We can also build any other workflow for your company, including one that runs several steps, in a Workflow Sprint or a scoped implementation. [Talk with us](https://fullypowered.ai/contact/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=finance-supplier-bill-review-and-payment-run-preparation&from=gh-supplier-bill-review-and-payment-run).
