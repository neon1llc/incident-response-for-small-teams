---
title: Response plan
description: "A one-page incident response plan: goals, roles, authority, severity levels, communication, records, and review."
---

**Business:** ______________________ **Version:** ____ **Approved by:** ______________________ **Date:** ____________ **Last tested:** ____________ **Next review:** ____________

## 1. Goals and scope

We will protect people and money first, keep the business running, preserve evidence, meet every notification duty on time, and learn from each incident. This plan covers every event that threatens our systems, data, or money, including incidents at vendors that hold our data. Systems and data covered: ______________________

## 2. Roles and authority

| Role | Name | Backup | May decide |
|---|---|---|---|
| Incident lead | | | Declare and close incidents, set severity, disconnect systems, call the insurer and lawyer, approve spending up to $______ |
| Tech lead | | | Contain and restore systems, within the lead's direction |
| Scribe | | | Keeps the incident log |
| Communications | | | Sends approved messages to staff, clients, and others |

Only the incident lead, with the lawyer, decides whether to notify anyone outside. Only the owner approves any ransom payment, after advice from the insurer and lawyer.

## 3. Reporting

Anyone who notices something unusual tells **______________________** at **______________________** right away and doesn't try to fix it. Nobody is blamed for reporting.

## 4. Severity levels

Levels are defined in [is this an incident?](../runbook/is-this-an-incident.md). Respond within 1 hour for level 1, the same day for level 2, and 1 business day for level 3. Log level 4.

## 5. How we respond and communicate

We follow Incident Response for Small Teams. Playbooks are kept at: ______________________

- **Backup channel** if email or chat is compromised: ______________________
- **Contact sheet** location, printed and digital: ______________________
- Outside messages are approved by the incident lead and lawyer.

## 6. Notification duties

- [ ] State breach laws where our clients and staff live: ______________________
- [ ] Industry rules, such as the FTC Safeguards Rule, HIPAA, Regulation S-P, or 23 NYCRR 500: ______________________
- [ ] Client contracts with notice deadlines: ______________________
- [ ] Cyber insurance notice requirement: within ______ hours or days

## 7. Records

The scribe logs every incident, including level 4. We keep logs, notification decisions, notices, and after-action reports for ______ years.

## 8. Fixing weaknesses

Every level 1 or 2 incident gets an after-action review within two weeks. Each fix gets an owner and a date, tracked at: ______________________

## 9. Testing and review

We run a tabletop exercise at least yearly. We review this plan after every level 1 or 2 incident, every exercise, and any big change to staff or systems.

**Signed:** ______________________ **Date:** ____________

## Sources

- [16 CFR 314.4](https://www.ecfr.gov/current/title-16/section-314.4), FTC Safeguards Rule: the seven areas a written incident response plan must address, at paragraph (h).
- [Incident Response Plan Basics](https://www.cisa.gov/sites/default/files/publications/Incident-Response-Plan-Basics_508c.pdf), from CISA: plan elements for small organizations.
- [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final), from NIST: roles, policies, and plans for incident response.
