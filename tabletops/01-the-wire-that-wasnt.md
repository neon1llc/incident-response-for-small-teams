---
title: The wire that wasn't
description: "A tabletop exercise on business email compromise: a supplier's new bank details, a paid invoice, and a supplier who says they were never paid."
---

**Time:** 60 to 90 minutes. **Playbook:** [business email compromise](../playbooks/business-email-compromise.md).

## Setup

**Attend:** the owner, whoever approves and sends payments, the office manager, and IT or the MSP.

**Objectives:**

1. Know who calls the bank, on what number, and how fast.
2. Find out whether the payment change process would have stopped this.
3. Decide when a payment fraud becomes a possible data breach.

**Prepare:** replace "Brightline Office Supply" with a real vendor the business pays monthly, and use a realistic invoice amount.

## Inject 1: Tuesday, 10:20am

Your bookkeeper gets an email from your regular contact at Brightline Office Supply. It's a normal thread about this month's invoice, with one new line: "We've moved banks. Please use the attached details for this and future payments." The invoice is $18,400, due Friday. The email address looks right.

**Ask:**
- What happens next here, step by step, as things work today?
- Is there a written rule for bank detail changes? Who knows it?
- Who could approve this payment alone?

## Inject 2: the following Monday, 9:05am

Brightline calls. They haven't received Friday's payment, and their bank details haven't changed. Your bookkeeper confirms the wire went out Friday at 2pm to the new account.

**Ask:**
- Who's told first, and how? Is this an incident? What severity?
- Who calls the bank, on which number, and what exactly do they ask for?
- Who reports it to IC3? What do they need to have in hand?
- Is the insurer called? Does the policy cover social engineering fraud?

## Inject 3: Monday, 11:30am

Your IT provider finds that the email came from Brightline's real account, which was hacked. They also find that three days before the fake email, someone signed in to **your bookkeeper's** mailbox from another country and created a rule moving any message containing "Brightline" to a folder called Archive2.

**Ask:**
- What does that change? What else could the attacker read in the bookkeeper's mailbox?
- What has to happen to the bookkeeper's account right now?
- Do clients or staff need to be told? Who decides, and with whom?

## Inject 4 (optional): Monday, 3pm

Two of your clients call. Each got an email from your bookkeeper's address with a "revised invoice" and new payment details.

**Ask:**
- What do you tell them, and through what channel?
- Who else might have received one?

## What good looks like

- The bank is called within an hour of the discovery, and the IC3 report filed the same day. See the [first hour](../runbook/first-hour.md).
- Inject 3 raises the severity: this is now a [compromised account](../playbooks/compromised-account.md), and the mailbox contents drive [notify](../runbook/notify.md).
- Clients are warned by phone or another channel, not from the compromised mailbox.
- The team names the missing control: a callback to a known number before any change to payment details.

## Debrief

1. Where did we lose time, or where would we have?
2. Did everyone know where the bank's fraud line was written down?
3. Would our current process have caught inject 1? What one change would?

Record it on the [tabletop record](../templates/tabletop-record.md).

## Sources

- [Business email compromise](https://www.fbi.gov/how-we-can-help-you/scams-and-safety/common-frauds-and-scams/business-email-compromise), from the FBI: vendor bank change fraud and immediate reporting.
- [Internet Crime Complaint Center](https://www.ic3.gov/), from the FBI: reporting fraudulent transfers quickly.
- [CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages), from CISA: the exercise format.
