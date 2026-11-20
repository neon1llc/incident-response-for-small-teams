---
title: Investigate
description: "Find out how the attacker got in, how long they were there, and whose information they could reach."
---

For a level 1 or 2 incident, the forensics firm (often assigned by your insurer, through your lawyer) leads. Your job is to preserve what they need and answer quickly.

## The four questions

1. **How did they get in?** A phished or reused password, an unpatched device, a remote access tool, a vendor's account?
2. **When?** The first sign of access, not the day someone noticed. The gap is often weeks.
3. **What could they reach, and what did they do?** Read, download, change, delete, encrypt, send, or pay.
4. **Whose information was in reach?** Clients, staff, or patients, and which kinds of data: Social Security numbers, tax returns, bank and card numbers, health records, passwords, ID documents.

Question 4 drives [notify](notify.md). "We don't know what they opened" usually means treating everything in reach as exposed.

## What to collect

- **Sign-in and audit logs** from the Microsoft 365 or Google Workspace admin center (Purview or the audit and investigation tool) and other cloud apps: where accounts were used, mail read, files downloaded, settings changed.
- **The mailbox:** forwarding and inbox rules, sent and deleted items.
- **Devices,** left as they are, and **firewall and VPN logs:** malware, remote access tools, large uploads.
- **Bank and payment records:** transfers and payee changes.
- **People,** interviewed and written up the same day: what they clicked, approved, or were asked to do.

Export logs to files stored outside the affected accounts, and note who exported them and when. That record is your chain of custody if the incident reaches a regulator or court.

When a lawyer hires the forensics firm, its findings may be protected as legal advice, so route requests and reports through the lawyer. Keep your own log factual: what was seen and done, not guesses about blame.

Summarize in the log how they got in, the dates of access, what was reached, what was taken or changed, and the evidence for each. It feeds the [notification worksheet](../templates/notification-worksheet.md) and the [after-action report](../templates/after-action-report.md).

## Sources

- [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final), from NIST: incident analysis (RS.AN), including root cause, scope, and preserving evidence and its integrity.
- [Data Breach Response: A Guide for Business](https://www.ftc.gov/business-guidance/resources/data-breach-response-guide-business), from the FTC: bring in forensics experts and legal counsel, and interview the people involved.
- [Secure Cloud Business Applications (SCuBA)](https://www.cisa.gov/resources-tools/services/secure-cloud-business-applications-scuba-project), from CISA: logging and audit settings for Microsoft 365 and Google Workspace.
