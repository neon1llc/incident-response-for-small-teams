---
title: The runbook
description: "How a small business handles a security incident, from the first report to the lessons learned, in the order the work happens."
---

Written for people who don't do security for a living, to follow under stress. Before you adopt it, confirm roles, systems, escalation, and legal requirements with the people responsible. Print the [first hour](first-hour.md) and keep a copy away from the computers it protects.

## The pages, in order

| Step | Page | What it settles |
|---|---|---|
| Before | [Get ready](get-ready.md) | Who does what, who you'll call, and what you'll need |
| Spot it | [Is this an incident?](is-this-an-incident.md) | Events, incidents, breaches, and four severity levels |
| 0:00 to 1:00 | [The first hour](first-hour.md) | Report, declare, assign roles, stop the damage, start the log |
| Hours | [Contain](contain.md) | Cut off the attacker without destroying evidence |
| Hours to days | [Investigate](investigate.md) | What happened, how they got in, whose data was touched |
| Days | [Notify](notify.md) | Who to tell, by when, and what to say |
| Days to weeks | [Recover](recover.md) | Clean rebuilds, safe restores, watching for a return |
| Within two weeks | [Learn](learn.md) | The review and the fixes that come out of it |

For a specific kind of incident, the [playbooks](../playbooks/index.md) add what's different. To practice first, run a [tabletop exercise](../tabletops/index.md).

## The roles

Every incident has these four jobs. One person may hold two, but the lead and the scribe should differ.

| Role | Does | Usually |
|---|---|---|
| **Incident lead** | Declares the incident, sets priorities, makes the calls: disconnect, notify, spend | The owner, or whoever they name |
| **Tech lead** | Contains, investigates, and restores, or directs the IT provider who does | The IT person or managed service provider (MSP) |
| **Scribe** | Keeps the [incident log](../templates/incident-log.md) with times | Anyone calm and careful |
| **Communications** | Talks to staff, clients, and outsiders using wording the lead and lawyer approved | The office manager or owner |

Outside help (the insurer's breach coach, a lawyer, a forensics firm) advises. The incident lead decides.

## Mistakes that make incidents worse

- **Waiting to be sure.** Standing down a false alarm costs minutes. A late start can cost a notification deadline.
- **Cleaning up first.** Wiping a laptop or deleting the attacker's rules destroys evidence of what was taken.
- **Talking in the compromised account.** Use the phone or backup channel.
- **Everyone on everything.** Name the roles, give each person one thing, and keep check-ins short and regular.
- **Hiring help before calling the insurer.** Many policies only pay for the firms they assign.
- **Skipping the review.** The same gap causes the next incident.

## Sources

- [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final), from NIST: incident response recommendations organized around the CSF 2.0 functions.
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework), from NIST: the six functions and their categories.
- [Incident Response Plan Basics](https://www.cisa.gov/sites/default/files/publications/Incident-Response-Plan-Basics_508c.pdf), from CISA: the plan elements and roles a small organization needs.
