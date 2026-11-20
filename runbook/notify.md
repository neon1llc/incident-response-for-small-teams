---
title: Notify
description: "Who to tell after an incident, in what order, by when, and how to say it: insurer, lawyer, law enforcement, the people affected, regulators, and clients."
---

Small businesses often get hurt here, after the incident: a deadline missed because nobody knew it applied, or a message to clients that promised more than the facts supported. Decide who to notify with your lawyer, because requirements vary by jurisdiction, sector, and contract. [Notification rules](../reference/notification-rules.md) gives example deadlines with sources.

## Who, in order

| When | Who | Why |
|---|---|---|
| First hour | **Your bank**, if money moved | Recalls and freezes work best in the first hours |
| First hours | **Your cyber insurer** | Many policies require prompt notice and pick the lawyers and forensics firm |
| First day | **A lawyer**, ideally one who handles breaches | Decides which laws apply and whether a "breach" happened under each |
| First days | **Law enforcement**: ic3.gov for fraud and intrusions, the FBI or Secret Service field office for large losses, and CISA at cisa.gov/report | Helps recover funds and find decryption keys, and some laws let them ask you to delay public notice |
| As the law sets | **People whose information was exposed** | Every state requires it for certain personal information, on its own timeline. New York's GBL § 899-aa requires notice without unreasonable delay and within 30 days of discovery |
| As the law sets | **Regulators**: state attorneys general, the FTC, HHS, the IRS, and others | Depends on your industry, the data, and where affected people live |
| As your contracts set | **Clients and partners** whose data you hold | Contracts and business associate agreements often set their own deadlines |
| When needed | **Staff** | They'll get questions, and some of their data may be involved |

## The clock

Most deadlines run from **discovery**: the day anyone in the company, other than the attacker, knew or should have known. That's often the day of the first report, not the day the investigation finished. Write the discovery date in the [incident log](../templates/incident-log.md) and [notification worksheet](../templates/notification-worksheet.md) as soon as it's clear.

Law enforcement can ask you to delay notice so it doesn't harm an investigation. Get that request in writing.

## Working out what applies

Your lawyer will ask what kinds of data were in reach, whether it was encrypted and the key exposed, how many people and in which states, what kind of business you are, and whose data it is. If you hold it for a client, you usually tell the client, and the client tells the people affected. The [notification worksheet](../templates/notification-worksheet.md) collects all of it.

## What to say

A notice to affected people should say, in plain words:

- What happened and when.
- What information was involved.
- What you've done about it.
- What they can do: change passwords, watch accounts, place a fraud alert or credit freeze, and file an IRS Identity Protection PIN request if tax data was involved.
- How to reach you.

Don't guess, and don't minimize. "We have no evidence that your information was misused" is fair only when you looked and found none. Have the lawyer approve every outside message, and give staff a short script.

## Sources

- [Data Breach Response: A Guide for Business](https://www.ftc.gov/business-guidance/resources/data-breach-response-guide-business), from the FTC: notifying law enforcement, affected businesses, and individuals, with a model letter.
- [Security breach notification laws](https://www.ncsl.org/technology-and-communication/security-breach-notification-laws), from the National Conference of State Legislatures: every state's breach notification statute.
- [New York General Business Law § 899-aa](https://www.nysenate.gov/legislation/laws/GBS/899-AA), from the New York State Senate: the 30-day deadline and the state agencies to notify.
- [16 CFR 314.4](https://www.ecfr.gov/current/title-16/section-314.4), FTC Safeguards Rule: when a notification event counts as discovered, at paragraph (j)(2).
- [Internet Crime Complaint Center](https://www.ic3.gov/), from the FBI: reporting online fraud and intrusions.
- [Report a cyber incident](https://www.cisa.gov/report), from CISA: voluntary reporting for any organization.
