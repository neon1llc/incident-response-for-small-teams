---
title: The forwarding rule
description: "A tabletop exercise on a compromised mailbox: a quiet forwarding rule, three weeks of client email sent outside, and logs that may not reach back far enough."
---

**Time:** 60 to 90 minutes. **Playbook:** [compromised account](../playbooks/compromised-account.md).

## Setup

**Attend:** the owner, IT or the MSP, and a staff member who handles client documents by email.

**Objectives:**

1. Practice locking an attacker out of a cloud account completely.
2. Find out how far back your logs go, and what they can show.
3. Scope the notification decision when the evidence is incomplete.

**Prepare:** check which Microsoft 365 or Google Workspace plan the business has. The answer changes inject 3.

## Inject 1: Wednesday, 4:10pm

A client calls: they got an email from your associate asking them to "re-upload last year's documents" through a link. Your associate didn't send it. Your associate also mentions they've had a few MFA prompts on their phone this month and "just approved one to make it stop."

**Ask:**
- What happens in the next 30 minutes? Who does it, from which device?
- What should be checked on the account before anything is changed?
- What do you tell the client who called?

## Inject 2: Wednesday, 5:00pm

IT finds a rule on the associate's mailbox, created 23 days ago, forwarding every incoming message to an outside Gmail address. It also finds sign-ins from two other countries.

**Ask:**
- What does the forwarding rule mean for client data? What kinds of documents does this person get by email?
- Who calls the insurer and lawyer, and is this level 1 or 2?
- What about the other mailboxes? How would you know if they're affected?

## Inject 3: Thursday, 10:00am

IT reports that your plan's audit log covers only the last 14 days of mail access. The forwarding rule itself proves that every message received in the past 23 days left the company.

**Ask:**
- What can you say for sure about what was taken, and what can't you?
- How do you build the list of affected people from 23 days of incoming mail?
- Who needs to be told, and by when? Use the [notification worksheet](../templates/notification-worksheet.md).

## What good looks like

- The rule is screenshotted, then removed, and the password, sessions, and MFA are reset from a clean device. See [contain](../runbook/contain.md).
- Logs are exported at once, before more days roll off. See [investigate](../runbook/investigate.md).
- The team treats all forwarded mail as acquired, since the forwarding proves it left, and builds the list of people from it.
- "Approved a prompt to make it stop" comes up in the debrief as a training and MFA-strength issue, without blame.

## Curveballs

- The associate's mailbox is also a shared inbox the whole office uses for client intake.
- The attacker used the account to send the "re-upload" email to 400 contacts.

## Debrief

1. How long do our logs last, and is that enough?
2. Would we notice a new forwarding rule? Do we have an alert?
3. What would it take to move our admins to phishing-resistant MFA?

Record it on the [tabletop record](../templates/tabletop-record.md).

## Sources

- [Secure Cloud Business Applications (SCuBA)](https://www.cisa.gov/resources-tools/services/secure-cloud-business-applications-scuba-project), from CISA: logging, forwarding restrictions, and alerting for Microsoft 365 and Google Workspace.
- [Implementing phishing-resistant MFA](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf), from CISA: push fatigue and MFA that can't be phished.
- [CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages), from CISA: the exercise format.
