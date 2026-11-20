---
title: Left in the cab
description: "A tabletop exercise on a lost laptop: client files, no proof of encryption, and a decision about notifying."
---

**Time:** 60 minutes. **Playbook:** [lost or stolen device](../playbooks/lost-or-stolen-device.md). **Attend:** the owner, IT or the MSP, and one or two staff who carry work laptops or phones. **Prepare:** know which device management tool, if any, you use.

## Inject 1: Thursday, 7:40pm

A senior staff member texts the owner. She left her work laptop in a rideshare, and the driver isn't answering. It has Outlook, a synced copy of the client files folder, and a browser with saved passwords.

**Ask:** What happens tonight, and who does it? Can anyone lock or wipe the laptop?

## Inject 2: Friday, 9:00am

IT finds the laptop isn't enrolled in device management. Nobody knows whether BitLocker was on. The staff member says it "had a password."

**Ask:** Does "it had a password" mean the data is protected? How do you find out whether encryption was on?

## Inject 3: Friday, 2:00pm

The synced folder held about 340 client files, including tax returns for clients in New York, New Jersey, and Connecticut. Nothing shows the disk was encrypted.

**Ask:** Is this a breach, and under which laws? Use the [notification worksheet](../templates/notification-worksheet.md). When did the clock start?

## What good looks like

- Sessions are revoked and passwords changed Thursday night, not Friday. See [contain](../runbook/contain.md).
- The team sees that a sign-in password isn't encryption, and that without evidence the data counts as unencrypted.
- The discovery date is Thursday evening, and three states' laws may apply. See [notification rules](../reference/notification-rules.md).

**Debrief:** How many of our devices could we show are encrypted today?

## Sources

- [16 CFR 314.2](https://www.ecfr.gov/current/title-16/section-314.2), FTC Safeguards Rule: notification events involve unencrypted customer information.
- [New York General Business Law § 899-aa](https://www.nysenate.gov/legislation/laws/GBS/899-AA), from the New York State Senate: encrypted data and the 30-day deadline.
- [CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages), from CISA: the exercise format.
