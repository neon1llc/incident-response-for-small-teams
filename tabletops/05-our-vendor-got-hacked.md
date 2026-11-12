---
title: Our vendor got hacked
description: "A tabletop exercise on a vendor breach: a key software provider or IT company is breached, the details are thin, and your clients start calling."
---

**Time:** 60 to 90 minutes. **Playbook:** [vendor breach](../playbooks/vendor-breach.md).

## Setup

**Attend:** the owner, IT or the MSP (or someone else, if the MSP is the vendor in the scenario), and whoever talks to clients.

**Objectives:**

1. Find out whether you know which vendors hold which data.
2. Practice cutting a vendor's access when you depend on them.
3. Settle who notifies the people affected when the breach isn't yours.

**Prepare:** pick the business's most important vendor: its tax or practice management software, its cloud file service, or its MSP. Have the contract handy if you can.

## Inject 1: Monday, 8:30am

Your practice management software provider, used for client records and the client portal, emails all customers: "We are investigating a cybersecurity incident affecting some customer environments. We will share more information as it becomes available."

**Ask:**
- How do you confirm the email is real?
- What data does this vendor hold for you? Where is that written down?
- What do you change today, and can you still work?

## Inject 2: Tuesday

The vendor's status page says an attacker had access to "a subset of customer databases" for nine days. Your account manager doesn't know whether your data was in the subset. A tech news site names the vendor.

**Ask:**
- Who asks the vendor for answers, and what exactly do you ask, in writing?
- What does the contract say about breach notice and deadlines?
- Do you call your insurer and lawyer now, or wait for facts?

## Inject 3: Wednesday

Two clients call. They read the news and want to know if their information is safe. One says they got a phishing email that used their real client portal username.

**Ask:**
- What can you honestly tell them today?
- Who gives the official notice to clients if their data was taken: you or the vendor?
- What do you tell all clients about phishing that looks like it's from you or the portal?

## Inject 4 (optional): Friday

The vendor confirms your database was accessed. It offers to send notices on your behalf.

**Ask:**
- Do you accept? What would you need to see first?
- Whose deadline is it, and when did your clock start?

## What good looks like

- Shared passwords and keys are rotated, and the vendor's access to your systems is limited until it's explained. See [contain](../runbook/contain.md).
- Questions go to the vendor in writing, and answers are saved in the [incident log](../templates/incident-log.md).
- The team understands that clients are its own relationship, so notice duties may sit with the business even though the breach was the vendor's. See [notify](../runbook/notify.md).
- Client messages say only what's known, and warn about phishing.

## Curveballs

- The vendor is your MSP, which has remote access to every computer in the office.
- The vendor stops answering emails.

## Debrief

1. Do we have a list of vendors and what each holds?
2. What notice terms do our contracts have? Do they need changing?
3. Could we work for a week without this vendor?

Record it on the [tabletop record](../templates/tabletop-record.md).

## Sources

- [16 CFR 314.4](https://www.ecfr.gov/current/title-16/section-314.4), FTC Safeguards Rule: overseeing service providers.
- [New York General Business Law § 899-aa](https://www.nysenate.gov/legislation/laws/GBS/899-AA), from the New York State Senate: a business holding data it doesn't own must notify the owner.
- [CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages), from CISA: the exercise format.
