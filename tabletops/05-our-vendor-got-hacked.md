---
title: Our vendor got hacked
description: "A tabletop exercise on a vendor breach: the details are thin and your clients start calling."
---

**Time:** 60 to 90 minutes. **Playbook:** [vendor breach](../playbooks/vendor-breach.md). **Attend:** the owner, IT or the MSP (or someone else, if the MSP is the vendor), and whoever talks to clients. **Prepare:** pick your most important vendor, such as tax or practice management software, a cloud file service, or your MSP, and have the contract handy.

## Inject 1: Monday, 8:30am

Your practice management provider, which holds client records and runs the client portal, emails all customers: "We are investigating a cybersecurity incident affecting some customer environments. We will share more information as it becomes available."

**Ask:** How do you confirm the email is real? What data does this vendor hold for you, and where is that written down?

## Inject 2: Tuesday

The vendor's status page says an attacker had access to "a subset of customer databases" for nine days. Your account manager doesn't know whether yours was in it.

**Ask:** What do you ask the vendor, in writing? What does the contract say about breach notice? Do you call the insurer and lawyer now?

## Inject 3: Wednesday

Two clients call after reading the news. One got a phishing email that used their real portal username.

**Ask:** What can you honestly tell them? Who gives official notice, you or the vendor?

## What good looks like

- Shared passwords and keys are rotated, and the vendor's access is limited until explained. See [contain](../runbook/contain.md).
- Questions go to the vendor in writing, and answers go in the [incident log](../templates/incident-log.md).
- Clients are your relationship, so notice duties may be yours even though the breach was the vendor's. See [notify](../runbook/notify.md).
- Client messages say only what's known and warn about phishing.

**Debrief:** Do we have a list of vendors and what each holds?

## Sources

- [16 CFR 314.4](https://www.ecfr.gov/current/title-16/section-314.4), FTC Safeguards Rule: overseeing service providers.
- [New York General Business Law § 899-aa](https://www.nysenate.gov/legislation/laws/GBS/899-AA), from the New York State Senate: a business holding data it doesn't own must notify the owner.
- [CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages), from CISA: the exercise format.
