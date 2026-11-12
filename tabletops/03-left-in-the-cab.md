---
title: Left in the cab
description: "A tabletop exercise on a lost laptop: client files, a question about encryption nobody can answer, and a decision about notifying."
---

**Time:** 60 minutes. **Playbook:** [lost or stolen device](../playbooks/lost-or-stolen-device.md).

## Setup

**Attend:** the owner, IT or the MSP, and one or two staff who carry work laptops or phones.

**Objectives:**

1. Find out whether anyone can show, not guess, that work devices are encrypted.
2. Practice cutting a device's access to email and files.
3. Work out when a lost device becomes a breach.

**Prepare:** know which device management tool, if any, the business uses.

## Inject 1: Thursday, 7:40pm

A senior staff member texts the owner: she left her work laptop in a rideshare on the way home from a client meeting. The driver isn't answering. The laptop has Outlook, a synced copy of the client files folder, and a browser with saved passwords.

**Ask:**
- What happens tonight, and who does it? Can it wait until morning?
- Can anyone lock or wipe the laptop remotely? From where?
- Which accounts and passwords need to change?

## Inject 2: Friday, 9:00am

The rideshare company has no record of it being found. IT checks: the laptop isn't enrolled in device management. Nobody knows whether BitLocker was turned on. The staff member says it "had a password."

**Ask:**
- Does "it had a password" mean the data is protected? Why or why not?
- How would you find out whether encryption was on, now that the device is gone?
- What was in the synced folder? How would you list it?

## Inject 3: Friday, 2:00pm

IT finds the synced folder held about 340 client files, including tax returns for clients in New York, New Jersey, and Connecticut. There's no way to show the disk was encrypted.

**Ask:**
- Is this a breach? Under which laws? Use the [notification worksheet](../templates/notification-worksheet.md).
- Who calls the lawyer and the insurer?
- When did the notification clock start?

## What good looks like

- The laptop's sessions are revoked and passwords changed Thursday night, not Friday. See [contain](../runbook/contain.md).
- The team sees that a sign-in password isn't encryption, and that without proof, the data is treated as unencrypted.
- The discovery date is Thursday evening, and the team knows three states' laws may apply. See [notification rules](../reference/notification-rules.md).

## Curveballs

- On Monday, the laptop is returned by the driver, powered off. Does that end it?
- The staff member had also saved a client spreadsheet to the laptop's desktop, outside the synced folder.

## Debrief

1. How many of our devices could we prove are encrypted today?
2. Should client files be synced to laptops at all?
3. Who can lock or wipe a device after hours?

Record it on the [tabletop record](../templates/tabletop-record.md).

## Sources

- [16 CFR 314.2](https://www.ecfr.gov/current/title-16/section-314.2), FTC Safeguards Rule: notification events involve unencrypted customer information.
- [New York General Business Law § 899-aa](https://www.nysenate.gov/legislation/laws/GBS/899-AA), from the New York State Senate: encrypted data and the 30-day deadline.
- [CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages), from CISA: the exercise format.
