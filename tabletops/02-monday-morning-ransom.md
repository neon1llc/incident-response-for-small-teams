---
title: Monday morning ransom
description: "A tabletop exercise on ransomware: locked files across the office, a ransom note, untested backups, and a threat to publish client data."
---

**Time:** 90 minutes. **Playbook:** [ransomware](../playbooks/ransomware.md).

## Setup

**Attend:** the owner, IT or the MSP, the office manager, and whoever talks to clients.

**Practice:** isolating systems without destroying evidence, judging whether backups would work and how fast, and deciding about payment.

**Prepare:** list your real file server or shared drive, backup method, and line-of-business software.

## Inject 1: Monday, 8:15am

Three staff can't open files on the shared drive. The names end in `.lockd`. One computer shows a desktop file called `READ_ME_NOW.txt`.

**Ask:**
- Who gets the first call? Who declares the incident?
- What does each person do with their computer? Do you disconnect the whole office?

## Inject 2: Monday, 9:00am

The note says your files are encrypted and 120 GB was copied out. It demands $85,000 in cryptocurrency within 72 hours or the data goes on a leak site, and links to a chat for "support."

**Ask:**
- Who calls the insurer? Does anyone know the policy number without a computer?
- Does anyone contact the attackers? Who decides?

## Inject 3: Monday, 11:00am

IT reports that the nightly backup drive was plugged in and is also encrypted. A cloud backup exists, but nobody has restored from it in over a year. The attackers came in through a remote access tool with a password reused from a breached site.

**Ask:**
- How long can you run without these files? What comes back first?
- Who checks the cloud backup is complete and clean?

## Inject 4: Wednesday

The forensics firm confirms that a folder of client tax returns and IDs was copied. The leak site posts five client documents.

**Ask:**
- Who must be notified, by when? Use the [notification worksheet](../templates/notification-worksheet.md).
- Does publication change the payment discussion?

## What good looks like

- Affected computers are disconnected and left on, and the backup drive is unplugged. See [contain](../runbook/contain.md).
- The insurer is the first outside call after IT, and nobody contacts the attackers alone.
- The team treats it as a data breach from inject 2 and confirms it in inject 4. See [notify](../runbook/notify.md).
- Payment is the owner's decision with the insurer and lawyer, including sanctions risk.

## Debrief

1. How long would we be down? When did we last restore from backup?
2. Which accounts have remote access, and do all have MFA?

Record it on the [tabletop record](../templates/tabletop-record.md).

## Sources

- [Ransomware Guide](https://www.cisa.gov/stopransomware/ransomware-guide), from CISA: response checklist, backups, and data theft before encryption.
- [Updated advisory on potential sanctions risks for facilitating ransomware payments](https://ofac.treasury.gov/media/912981/download), from the Treasury Department's OFAC: sanctions risk in paying.
- [CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages), from CISA: the exercise format.
