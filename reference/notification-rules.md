---
title: Notification rules
description: "U.S. federal and New York rules that set who a small business must notify after a data incident, and by when, with links to the rule text."
---

This is a starting map for a talk with your lawyer, not legal advice. It covers only some U.S. federal rules and New York law. Other states and countries set their own. Rules change, and each defines "breach," "personal information," and "discovery" differently, so check the linked text before relying on a deadline. If personal information may be involved, call your lawyer and your cyber insurer first. Many policies set their own notice deadline.

## Every business: state breach laws

All 50 states, the District of Columbia, and the U.S. territories have breach notification laws. Each covers its own residents, so clients in three states can mean three laws. Most apply when unencrypted personal information, such as a name with a Social Security, driver's license, or financial account number, is acquired without authorization. See the [NCSL list](https://www.ncsl.org/technology-and-communication/security-breach-notification-laws).

**New York** ([General Business Law § 899-aa](https://www.nysenate.gov/legislation/laws/GBS/899-AA)):

- Notify affected New York residents without unreasonable delay and **within 30 days of discovery**, unless law enforcement asks for a delay.
- If you only hold the data for its owner, notify the owner immediately and within 30 days.
- When any New York residents are notified, also notify the **Attorney General, the Department of State, and the Division of State Police**, and the **Department of Financial Services** if you're a DFS-regulated business. Report through the Attorney General's [data breach reporting](https://ag.ny.gov/resources/organizations/data-breach-reporting) page.
- If more than 5,000 New York residents are notified at one time, also notify the consumer reporting agencies.
- New York's definition of private information includes medical information.
- [§ 899-bb](https://www.nysenate.gov/legislation/laws/GBS/899-BB) separately requires reasonable safeguards, scaled to a small business. It sets no notice deadline.

## By kind of business

| If you are | Rule | Who to notify | Deadline |
|---|---|---|---|
| A **tax preparer, mortgage broker, or other non-bank financial business** under the FTC | [FTC Safeguards Rule, 16 CFR 314.4(j)](https://www.ecfr.gov/current/title-16/section-314.4) | The FTC, through the form on ftc.gov, when unencrypted customer information of **500 or more consumers** was acquired without authorization | As soon as possible, and **no later than 30 days** after discovery |
| A **tax preparer** | IRS guidance in [Publication 4557](https://www.irs.gov/pub/irs-pdf/p4557.pdf) and [data theft information for tax professionals](https://www.irs.gov/individuals/data-theft-information-for-tax-professionals) | Your [IRS Stakeholder Liaison](https://www.irs.gov/businesses/small-businesses-self-employed/stakeholder-liaison-contacts), and the state tax agencies where you file, using the Federation of Tax Administrators' [Report a Data Breach](https://taxadmin.org/report-a-data-breach/) contacts | As soon as you know. Quick reports help the IRS block fraudulent returns in clients' names |
| A **health practice or health plan** (HIPAA covered entity) | [HIPAA Breach Notification Rule, 45 CFR 164 Subpart D](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-D) | Affected individuals. HHS. Prominent media too, if more than 500 residents of one state are affected | Individuals **without unreasonable delay and within 60 days** of discovery. HHS at the same time for 500 or more, or within 60 days after the end of the year for fewer than 500 |
| A **business associate** of a HIPAA covered entity | Same rule, 45 CFR 164.410 | The covered entity | **Without unreasonable delay and within 60 days** of discovery, or sooner if your agreement says so |
| A **health app or device company** outside HIPAA | [FTC Health Breach Notification Rule, 16 CFR 318](https://www.ecfr.gov/current/title-16/chapter-I/subchapter-C/part-318) | Affected individuals and the FTC. Media too, if 500 or more residents of one state | **Within 60 days** of discovery. The FTC at the same time for 500 or more |
| An **SEC-registered investment adviser, broker-dealer, investment company, or transfer agent** | [Regulation S-P, 17 CFR 248.30](https://www.ecfr.gov/current/title-17/section-248.30) | Affected individuals whose sensitive customer information was, or is reasonably likely to have been, accessed or used without authorization | As soon as practicable, and **no later than 30 days** after becoming aware. Your service providers must tell you within 72 hours. Compliance has been required since December 3, 2025 for larger firms and June 3, 2026 for smaller ones |
| A **DFS-regulated business** in New York, such as an insurance agency or licensed lender | [23 NYCRR Part 500](https://www.dfs.ny.gov/cybersecurity), section 500.17 | The Department of Financial Services | **Within 72 hours** of determining a reportable cybersecurity incident occurred. A ransom payment within 24 hours, with a written explanation within 30 days |
| A business that **takes card payments** | Your merchant agreement and the card brands' rules under PCI DSS | Your payment processor or acquiring bank | Usually immediately. Your merchant agreement sets it |
| A **critical infrastructure** business | The Cyber Incident Reporting for Critical Infrastructure Act (CIRCIA) | CISA | 72 hours for covered incidents and 24 hours for ransom payments, once CISA's final rule takes effect. Check [CISA](https://www.cisa.gov/report) for its status |

## Contracts

Client contracts, business associate agreements, and vendor agreements often set their own notice window, sometimes shorter than any law's. The contract's wording counts.

## Law enforcement and reporting lines

| For | Report to |
|---|---|
| Wire fraud, business email compromise, ransomware, and other online crime | [ic3.gov](https://www.ic3.gov/), and your local FBI field office for large or fast-moving losses |
| Any cyber incident, voluntarily | CISA at [cisa.gov/report](https://www.cisa.gov/report) |
| Identity theft affecting people | [IdentityTheft.gov](https://www.identitytheft.gov/), which gives each person a recovery plan |

## Sources

- [Security breach notification laws](https://www.ncsl.org/technology-and-communication/security-breach-notification-laws), from the National Conference of State Legislatures: every state's statute.
- [New York General Business Law § 899-aa](https://www.nysenate.gov/legislation/laws/GBS/899-AA), from the New York State Senate: deadlines, agencies, and the 5,000-resident threshold.
- [16 CFR 314.2](https://www.ecfr.gov/current/title-16/section-314.2) and [16 CFR 314.4](https://www.ecfr.gov/current/title-16/section-314.4), FTC Safeguards Rule: the definition of a notification event and the 30-day FTC notice.
- [FTC Safeguards Rule: What Your Business Needs to Know](https://www.ftc.gov/business-guidance/resources/ftc-safeguards-rule-what-your-business-needs-know), from the FTC: which businesses the rule covers, including tax preparers.
- [45 CFR 164 Subpart D](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-D) and [Breach Notification Rule](https://www.hhs.gov/hipaa/for-professionals/breach-notification/index.html), from HHS: HIPAA notice to individuals, HHS, and the media.
- [16 CFR 318](https://www.ecfr.gov/current/title-16/chapter-I/subchapter-C/part-318), FTC Health Breach Notification Rule: notice for health apps and devices outside HIPAA.
- [17 CFR 248.30](https://www.ecfr.gov/current/title-17/section-248.30), Regulation S-P: the 30-day notice and the 72-hour service provider notice.
- [§ 899-bb](https://www.nysenate.gov/legislation/laws/GBS/899-BB), from the New York State Senate: the reasonable safeguards requirement and its small business provision.
- [Cybersecurity regulation](https://www.dfs.ny.gov/cybersecurity), from the New York Department of Financial Services: Part 500 and its incident notice.
- [Data theft information for tax professionals](https://www.irs.gov/individuals/data-theft-information-for-tax-professionals), from the IRS: reporting to the Stakeholder Liaison and to state tax agencies.
- [Safeguarding Taxpayer Data](https://www.irs.gov/pub/irs-pdf/p4557.pdf), IRS Publication 4557: data theft reporting steps for tax professionals.
- [Report a cyber incident](https://www.cisa.gov/report), from CISA: voluntary reporting, and CIRCIA updates.
