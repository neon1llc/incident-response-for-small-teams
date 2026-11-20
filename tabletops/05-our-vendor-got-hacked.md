---
title: Our vendor got hacked
description: "A tabletop exercise on a vendor breach: a key software provider or IT company is breached, the details are thin, and your clients start calling."
---

**Time:** 60 to 90 minutes. **Playbook:** [vendor breach](../playbooks/vendor-breach.md).

## Setup

**Attend:** the owner, IT or the MSP (or someone else, if the MSP is the vendor in the scenario), and whoever talks to clients.

**Practice:** knowing which vendors hold which data, cutting a vendor's access when you depend on them, and settling who notifies people when the breach isn't yours.

**Prepare:** pick your most important vendor, such as tax or practice management software, a cloud file service, or your MSP. Have the contract handy if you can.

## Inject 1: Monday, 8:30am

Your practice management provider, which holds client records and runs the client portal, emails all customers: "We are investigating a cybersecurity incident affecting some customer environments. We will share more information as it becomes available."

**Ask:**
- How do you confirm the email is real?
- What data does this vendor hold for you, and where is that written down?
- What changes today? Can you still work?

## Inject 2: Tuesday

The vendor's status page says an attacker had access to "a subset of customer databases" for nine days. Your account manager doesn't know whether yours was in it. A tech news site names the vendor.

**Ask:**
- What do you ask the vendor, in writing, and who asks?
- What does the contract say about breach notice and deadlines?
- Do you call the insurer and lawyer now or wait for facts?

## Inject 3: Wednesday

Two clients call after reading the news. One got a phishing email that used their real portal username.

**Ask:**
- What can you honestly tell them today?
- Who gives official notice if their data was taken, you or the vendor?

## Inject 4 (optional): Friday

The vendor confirms your database was accessed and offers to send notices for you.

**Ask:**
- Do you accept? What do you need to see first?
- Whose deadline is it, and when did your clock start?

## What good looks like

- Shared passwords and keys are rotated, and the vendor's access is limited until explained. See [contain](../runbook/contain.md).
- Questions go to the vendor in writing, and answers go in the [incident log](../templates/incident-log.md).
- Clients are your relationship, so notice duties may be yours even though the breach was the vendor's. See [notify](../runbook/notify.md).
- Client messages say only what's known and warn about phishing.

## Debrief

1. Do we have a list of vendors and what each holds?
2. What notice terms do our contracts have? Could we work a week without this vendor?

Record it on the [tabletop record](../templates/tabletop-record.md).

## Sources

- [16 CFR 314.4](https://www.ecfr.gov/current/title-16/section-314.4), FTC Safeguards Rule: overseeing service providers.
- [New York General Business Law § 899-aa](https://www.nysenate.gov/legislation/laws/GBS/899-AA), from the New York State Senate: a business holding data it doesn't own must notify the owner.
- [CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages), from CISA: the exercise format.
