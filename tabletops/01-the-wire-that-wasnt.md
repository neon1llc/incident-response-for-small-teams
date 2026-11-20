---
title: The wire that wasn't
description: "A tabletop exercise on business email compromise: new bank details, a paid invoice, and a supplier who was never paid."
---

**Time:** 60 to 90 minutes. **Playbook:** [business email compromise](../playbooks/business-email-compromise.md). **Attend:** the owner, whoever sends payments, the office manager, and IT or the MSP. **Prepare:** replace "Brightline Office Supply" with a vendor you pay monthly.

## Inject 1: Tuesday, 10:20am

Your bookkeeper gets an email from your regular contact at Brightline Office Supply, in a normal thread about this month's invoice: "We've moved banks. Please use the attached details for this and future payments." The invoice is $18,400, due Friday. The email address looks right.

**Ask:** What happens next, as things work today? Is there a written rule for bank detail changes?

## Inject 2: the following Monday, 9:05am

Brightline calls. They haven't been paid, and their bank details haven't changed. Your bookkeeper confirms the wire went out Friday at 2pm to the new account.

**Ask:** Who calls the bank, on which number, and what do they ask for? Who reports to IC3? Does the policy cover social engineering fraud?

## Inject 3: Monday, 11:30am

IT finds that the email came from Brightline's real account, which was hacked. Three days earlier, someone signed in to **your bookkeeper's** mailbox from another country and created a rule moving any message containing "Brightline" to a folder called Archive2.

**Ask:** What else could the attacker read? What happens to the account now? Who decides whether clients are told?

## What good looks like

- The bank is called within an hour of discovery, and the IC3 report is filed the same day. See the [first hour](../runbook/first-hour.md).
- Inject 3 makes it a [compromised account](../playbooks/compromised-account.md), and the mailbox contents drive [notify](../runbook/notify.md).

- The team names the missing control: a callback to a known number before any change to payment details.

**Debrief:** Did everyone know where the bank's fraud line is written down? What one change would have caught inject 1?

## Sources

- [Business email compromise](https://www.fbi.gov/how-we-can-help-you/scams-and-safety/common-frauds-and-scams/business-email-compromise), from the FBI: vendor bank change fraud and immediate reporting.
- [Internet Crime Complaint Center](https://www.ic3.gov/), from the FBI: reporting fraudulent transfers quickly.
- [CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages), from CISA: the exercise format.
