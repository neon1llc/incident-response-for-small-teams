---
title: Notify
description: "Who to tell after an incident, in what order, by when, and how to say it: insurer, lawyer, law enforcement, the people affected, regulators, and clients."
---

Small businesses often get hurt here after the incident itself: a deadline missed because nobody knew it applied, or a message to clients that promised more than the facts supported. Decide who to notify with your lawyer. Requirements vary by jurisdiction, sector, and contract. This page is the map, and [notification rules](../reference/notification-rules.md) gives example deadlines, each with the rule it comes from.

## Who, in order

| When | Who | Why |
|---|---|---|
| First hour | **Your bank**, if money moved | Recalls and freezes work best in the first hours |
| First hours | **Your cyber insurer** | Many policies require prompt notice and pick the lawyers and forensics firm |
| First day | **A lawyer**, ideally one who handles breaches | Decides which laws apply and whether a "breach" happened under each |
| First days | **Law enforcement**: ic3.gov for fraud and intrusions, the FBI or Secret Service field office for large losses, and CISA at cisa.gov/report | Helps recover funds and find decryption keys, and some laws let them ask you to delay public notice |
| As the law sets | **People whose information was exposed** | Every state requires it for certain personal information, on its own timeline. For example, New York's GBL § 899-aa requires notice without unreasonable delay and within 30 days of discovery |
| As the law sets | **Regulators**: state attorneys general, the FTC, HHS, the IRS, and others | Depends on your industry, the data, and where affected people live |
| As your contracts set | **Clients and partners** whose data you hold for them | Contracts and business associate agreements often set their own notice deadlines |
| When needed | **Staff** | They'll get questions, and some of their data may be involved too |

## The clock

Most deadlines run from **discovery**: the day anyone in the company, other than the attacker, knew or should have known. That's often the day of the first report, not the day the investigation finished. Write the discovery date in the [incident log](../templates/incident-log.md) and on the [notification worksheet](../templates/notification-worksheet.md) as soon as it's clear.

A law enforcement agency can ask you to delay notice so it doesn't harm an investigation. Get that request in writing.

## Working out what applies

The [notification worksheet](../templates/notification-worksheet.md) covers the facts your lawyer will ask for:

1. **What kinds of data** were in reach? Names with Social Security numbers, driver's license numbers, financial account numbers, health information, and account passwords trigger most laws.
2. **Was it encrypted**, and was the key also exposed?
3. **How many people**, and **in which states** do they live? Each state's law applies to its own residents.
4. **What kind of business are you?** Health practices, tax preparers, financial firms, and insurance agencies have extra rules.
5. **Whose data is it?** If you hold it for a client, you usually tell the client, and the client tells the people affected.

## What to say

A notice to affected people should say, in plain words:

- What happened, and when, in terms the reader understands.
- What information was involved.
- What you've done about it.
- What they can do: change passwords, watch accounts, place a fraud alert or credit freeze, and file an IRS Identity Protection PIN request if tax data was involved.
- How to reach you with questions.

Don't guess, and don't minimize. "We have no evidence that your information was misused" is fair only when you looked and found none. Have the lawyer approve every outside message, and give staff a short script.

## Sources

- [Data Breach Response: A Guide for Business](https://www.ftc.gov/business-guidance/resources/data-breach-response-guide-business), from the FTC: notifying law enforcement, affected businesses, and individuals, with a model letter.
- [Security breach notification laws](https://www.ncsl.org/technology-and-communication/security-breach-notification-laws), from the National Conference of State Legislatures: every state's breach notification statute.
- [New York General Business Law § 899-aa](https://www.nysenate.gov/legislation/laws/GBS/899-AA), from the New York State Senate: the 30-day deadline and the state agencies to notify.
- [16 CFR 314.4](https://www.ecfr.gov/current/title-16/section-314.4), FTC Safeguards Rule: when a notification event counts as discovered, at paragraph (j)(2).
- [Internet Crime Complaint Center](https://www.ic3.gov/), from the FBI: reporting online fraud and intrusions.
- [Report a cyber incident](https://www.cisa.gov/report), from CISA: voluntary reporting for any organization.
