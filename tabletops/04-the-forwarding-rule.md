---
title: The forwarding rule
description: "A tabletop exercise on a compromised mailbox: a quiet forwarding rule, three weeks of client email sent outside, and logs that may not reach back far enough."
---

**Time:** 60 to 90 minutes. **Playbook:** [compromised account](../playbooks/compromised-account.md).

## Setup

**Attend:** the owner, IT or the MSP, and a staff member who handles client documents by email.

**Practice:** locking an attacker out of a cloud account completely, finding out how far back your logs go, and scoping notification when evidence is incomplete.

**Prepare:** check which Microsoft 365 or Google Workspace plan you have. It changes inject 3.

## Inject 1: Wednesday, 4:10pm

A client calls. They got an email from your associate asking them to "re-upload last year's documents" through a link. Your associate didn't send it. They also mention a few MFA prompts this month and say they "just approved one to make it stop."

**Ask:**
- What happens in the next 30 minutes, and who does it from which device?
- What do you check before changing anything? What do you tell the client?

## Inject 2: Wednesday, 5:00pm

IT finds a rule on the associate's mailbox, created 23 days ago, forwarding every incoming message to an outside Gmail address. It also finds sign-ins from two other countries.

**Ask:**
- What does the rule mean for client data?
- Who calls the insurer and lawyer? Is this level 1 or 2?
- How would you know if other mailboxes are affected?

## Inject 3: Thursday, 10:00am

Your plan's audit log covers only the last 14 days of mail access. The rule itself proves every message received in 23 days left the company.

**Ask:**
- What can you say for sure about what was taken, and what can't you?
- How do you list the affected people from 23 days of mail?
- Who is told, and by when? Use the [notification worksheet](../templates/notification-worksheet.md).

## What good looks like

- The rule is screenshotted, then removed. Password, sessions, and MFA are reset from a clean device. See [contain](../runbook/contain.md).
- Logs are exported at once, before more days roll off. See [investigate](../runbook/investigate.md).
- All forwarded mail counts as acquired, and the list of people comes from it.
- "Approved a prompt to make it stop" becomes a training and MFA-strength topic, without blame.

## Debrief

1. How long do our logs last? Would we notice a new forwarding rule?
2. What would it take to move admins to phishing-resistant MFA?

Record it on the [tabletop record](../templates/tabletop-record.md).

## Sources

- [Secure Cloud Business Applications (SCuBA)](https://www.cisa.gov/resources-tools/services/secure-cloud-business-applications-scuba-project), from CISA: logging, forwarding restrictions, and alerting for Microsoft 365 and Google Workspace.
- [Implementing phishing-resistant MFA](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf), from CISA: push fatigue and MFA that can't be phished.
- [CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages), from CISA: the exercise format.
