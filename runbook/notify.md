---
title: Notify
description: "Who to tell after an incident, in what order, by when, and what to say."
---

Small businesses get hurt here by missing a deadline nobody knew applied, or by promising clients more than the facts supported. Decide who to notify with your lawyer, because requirements vary by jurisdiction, sector, and contract. [Notification rules](../reference/notification-rules.md) has example deadlines.

1. **Your bank,** in the first hour, if money moved. Recalls and freezes work best early.
2. **Your cyber insurer,** in the first hours. Many policies require prompt notice and pick the lawyers and forensics firm.
3. **A lawyer,** ideally one who handles breaches, on the first day. They decide which laws apply and whether a "breach" happened under each.
4. **Law enforcement,** in the first days: ic3.gov for fraud and intrusions, the FBI or Secret Service field office for large losses, and CISA at cisa.gov/report. They can help recover funds and find decryption keys, and some laws let them ask you to delay public notice.
5. **People whose information was exposed,** as the law sets. Every state requires it for certain personal information, on its own timeline. New York's GBL § 899-aa requires notice without unreasonable delay and within 30 days of discovery.
6. **Regulators,** as the law sets: state attorneys general, the FTC, HHS, the IRS, and others, depending on your industry, the data, and where affected people live.
7. **Clients and partners** whose data you hold, as your contracts set. Contracts often set their own deadlines.

## The clock

Most deadlines run from **discovery**: the day anyone in the company, other than the attacker, knew or should have known. That's often the day of the first report, not the day the investigation finished. Write the discovery date in the [incident log](../templates/incident-log.md) and [notification worksheet](../templates/notification-worksheet.md) as soon as it's clear. Get any law enforcement request to delay notice in writing.

Your lawyer will ask what data was in reach, whether it was encrypted and the key exposed, how many people live in which states, and whose data it is. If you hold it for a client, you usually tell the client, and the client tells the people affected. The [notification worksheet](../templates/notification-worksheet.md) collects all of it.

## What to say

A notice to affected people says, in plain words:

- What happened and when, and what information was involved.
- What you've done about it.
- What they can do: change passwords, watch accounts, place a fraud alert or credit freeze, and file an IRS Identity Protection PIN request if tax data was involved.
- How to reach you.

Don't guess or minimize. "We have no evidence that your information was misused" is fair only when you looked and found none. Have the lawyer approve every outside message, and give staff a short script.

## Sources

- [Data Breach Response: A Guide for Business](https://www.ftc.gov/business-guidance/resources/data-breach-response-guide-business), from the FTC: notifying law enforcement, affected businesses, and individuals, with a model letter.
- [Security breach notification laws](https://www.ncsl.org/technology-and-communication/security-breach-notification-laws), from the National Conference of State Legislatures: every state's breach notification statute.
- [New York General Business Law § 899-aa](https://www.nysenate.gov/legislation/laws/GBS/899-AA), from the New York State Senate: the 30-day deadline and the state agencies to notify.
- [16 CFR 314.4](https://www.ecfr.gov/current/title-16/section-314.4), FTC Safeguards Rule: when a notification event counts as discovered, at paragraph (j)(2).
- [Internet Crime Complaint Center](https://www.ic3.gov/), from the FBI: reporting online fraud and intrusions.
- [Report a cyber incident](https://www.cisa.gov/report), from CISA: voluntary reporting for any organization.
