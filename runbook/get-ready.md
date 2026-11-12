---
title: Get ready
description: "The work to do before an incident: a one-page plan, a contact sheet, the logs and backups you'll need, insurance, and a yearly drill."
---

Most of what goes wrong in an incident was decided months earlier: nobody knew who could approve shutting the office down, the insurer's number was in the hacked mailbox, or the backups had never been restored. An afternoon of preparation fixes most of that.

## The checklist

- [ ] **Write the plan.** Fill in the one-page [response plan](../templates/response-plan.md): roles and a backup for each, severity levels, who may approve what, and when a decision moves up to the owner. Have the owner sign it.
- [ ] **Fill in the contact sheet.** The [contact sheet](../templates/contact-sheet.md) lists your IT provider's after-hours number, insurer claim line and policy number, lawyer, bank fraud line, and key vendors. Print it. Keep one copy in the office and one at the lead's home.
- [ ] **Agree on a backup channel.** Decide now how you'll talk if email and chat are compromised: a group text, a phone tree, or a call bridge. Don't discuss an incident inside an account the attacker might be reading.
- [ ] **Know what you have.** Keep a short list of systems (email, file storage, accounting, line-of-business software, website), who administers each, and where personal information lives. You can't decide who to notify without it.
- [ ] **Turn on the logs.** Make sure sign-in and audit logs are on for email and cloud accounts, and kept for at least 90 days, longer where your plan allows. Many small-business plans keep very little by default.
- [ ] **Test a restore.** Back up what you can't lose, with one copy offline or immutable, and restore a real file from it every quarter.
- [ ] **Read your insurance policy.** Find out whether you have cyber coverage, how fast you must report, and whether you have to use the insurer's lawyers and forensics firms. Using your own can cost you coverage.
- [ ] **Line up help.** Know which forensics firm you'd call (often the insurer's), and get your IT provider's incident terms in writing: hours, rates, and what they will and won't do.
- [ ] **Tell staff how to report.** One name, one number, and the rule "tell us, don't fix it." Repeat it at onboarding and once a year.
- [ ] **Practice.** Run a [tabletop exercise](../tabletops/index.md) at least once a year, and after any big change to staff or systems. Fix what it finds.

## What regulators expect

Several rules require a written incident response plan, not only good intentions. The FTC Safeguards Rule, which covers tax preparers, mortgage brokers, car dealers that arrange financing, and other non-bank financial businesses, requires one. So does the HIPAA Security Rule for health practices and their business associates. Insurers ask about it on renewal forms, and SOC 2 auditors test it. The [response plan](../templates/response-plan.md) template covers the elements they look for. See [notification rules](../reference/notification-rules.md) for which rules may apply to you.

## Sources

- [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final), from NIST: preparation as part of Govern, Identify, and Protect.
- [Small Business Guide: Response and Recovery](https://www.ncsc.gov.uk/collection/small-business-guidance--response-and-recovery/step-1-prepare-for-incidents), from the UK National Cyber Security Centre: cover for absence, decision trigger points, and keeping contacts reachable.
- [Incident Response Plan Basics](https://www.cisa.gov/sites/default/files/publications/Incident-Response-Plan-Basics_508c.pdf), from CISA: plan elements, roles, and a backup communication channel.
- [16 CFR 314.4](https://www.ecfr.gov/current/title-16/section-314.4), FTC Safeguards Rule: the required written incident response plan, at paragraph (h).
- [45 CFR 164.308](https://www.ecfr.gov/current/title-45/section-164.308), HIPAA Security Rule: security incident procedures and contingency planning.
- [Ransomware Guide](https://www.cisa.gov/stopransomware/ransomware-guide), from CISA: offline backups, restore testing, and log retention.
- [Safeguarding Taxpayer Data](https://www.irs.gov/pub/irs-pdf/p4557.pdf), IRS Publication 4557: security and incident planning for tax professionals.
