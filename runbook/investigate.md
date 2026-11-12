---
title: Investigate
description: "Find out what happened, how the attacker got in, how long they were there, and whose information they could reach."
---

The investigation answers the questions every later decision depends on. For a level 1 or 2 incident, the forensics firm (often assigned by your insurer, through your lawyer) leads it. Your job is to preserve what they need and answer their questions quickly.

## The five questions

1. **How did they get in?** A phished password, a reused password, an unpatched device, a remote access tool, a vendor's account?
2. **When?** The first sign of access, not the day someone noticed. The gap is often weeks.
3. **What could they reach?** Every mailbox, folder, system, and account the compromised access could open.
4. **What did they do?** Read, download, change, delete, encrypt, send, or pay.
5. **Whose information was in reach?** Clients, staff, patients, and which kinds of data: Social Security numbers, tax returns, bank and card numbers, health records, passwords, ID documents.

The answer to question 5 drives [notify](notify.md). "We don't know what they opened" usually means treating everything in reach as exposed.

## What to collect

| Source | What it shows | Where |
|---|---|---|
| Sign-in logs | Where and when accounts were used, and from which devices | Microsoft 365 or Google Workspace admin center, other cloud apps |
| Audit logs | Mail read, files opened or downloaded, rules and settings changed | Microsoft Purview audit, Google Workspace audit and investigation |
| Mailbox | Forwarding and inbox rules, sent and deleted items, messages sent from the account | The mailbox itself and the admin center |
| Devices | Malware, remote access tools, browser sessions | The affected computers, kept as they are |
| Firewall and VPN logs | Connections in and out, large uploads | Your router, firewall, or IT provider |
| Bank and payment records | Transfers, payee changes, card activity | Online banking and the payment processor |
| People | What they clicked, opened, approved, or were asked to do | Short interviews, written down the same day |

Export logs to files and store them outside the affected accounts. Note who exported them and when. A simple record like this is your chain of custody if the incident ever reaches a regulator or a court.

## Working with lawyers and forensics

When a lawyer hires the forensics firm, their findings may be protected as legal advice. That protection is the lawyer's call to make and keep, so route forensics requests and reports through them. Keep your own log factual: what was seen and done, not guesses about blame.

## When you're done

Write a short summary in the log: how they got in, the dates of access, what was reached, what was taken or changed, and the evidence for each. This summary feeds the [notification worksheet](../templates/notification-worksheet.md) and the [after-action report](../templates/after-action-report.md).

## Sources

- [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final), from NIST: incident analysis (RS.AN), including root cause, scope, and preserving evidence and its integrity.
- [Data Breach Response: A Guide for Business](https://www.ftc.gov/business-guidance/resources/data-breach-response-guide-business), from the FTC: bring in forensics experts and legal counsel, and interview the people involved.
- [Secure Cloud Business Applications (SCuBA)](https://www.cisa.gov/resources-tools/services/secure-cloud-business-applications-scuba-project), from CISA: logging and audit settings for Microsoft 365 and Google Workspace.
