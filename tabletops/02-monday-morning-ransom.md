---
title: Monday morning ransom
description: "A tabletop exercise on ransomware: locked files across the office, a ransom note, untested backups, and a threat to publish client data."
---

**Time:** 90 minutes. **Playbook:** [ransomware](../playbooks/ransomware.md).

## Setup

**Attend:** the owner, IT or the MSP, the office manager, and whoever talks to clients.

**Objectives:**

1. Practice isolating systems without destroying evidence.
2. Find out whether backups would get the business running, and how long it would take.
3. Walk through the decision about paying, and who must be in the room for it.

**Prepare:** list the business's real file server or shared drive, backup method, and line-of-business software.

## Inject 1: Monday, 8:15am

Three staff can't open files on the shared drive. The file names end in `.lockd`. One computer shows a text file on the desktop called `READ_ME_NOW.txt`.

**Ask:**
- Who's the first call? Who declares the incident?
- What does each person do with their own computer right now?
- Do you disconnect the whole office? Who decides?

## Inject 2: Monday, 9:00am

The note says your files are encrypted and 120 GB of data was copied out. It demands $85,000 in cryptocurrency within 72 hours, or the data will be published on a leak site. It gives a chat link for "support."

**Ask:**
- Who calls the insurer, and does anyone know the policy number without a computer?
- Does anyone contact the attackers? Who decides, and when?
- What do staff tell clients who call today?

## Inject 3: Monday, 11:00am

Your IT provider reports: the nightly backup drive was plugged in and is also encrypted. Cloud backup of the shared drive exists, but nobody has restored from it in over a year. The attackers got in through a remote access tool with a password that was reused from a breached site.

**Ask:**
- How long can the business run without these files? What comes back first?
- Who checks whether the cloud backup is complete and clean?
- What had to be closed before restoring?

## Inject 4: Wednesday

The forensics firm confirms that a folder of client tax returns and IDs was copied out. The leak site posts a sample of five client documents.

**Ask:**
- Who must be notified, by when? Use the [notification worksheet](../templates/notification-worksheet.md).
- Does publication change the payment discussion? Why or why not?
- What do you tell the five clients whose documents were posted?

## What good looks like

- Affected computers are disconnected and left on. The backup drive is unplugged if it isn't yet. See [contain](../runbook/contain.md).
- The insurer is the first outside call after IT, and nobody contacts the attackers alone.
- The team treats it as a data breach from inject 2, since data theft was claimed, and confirms in inject 4. See [notify](../runbook/notify.md).
- Payment is discussed as a decision for the owner with the insurer and lawyer, including sanctions risk.

## Curveballs

- It's tax season: the second week of April.
- The IT provider can't come on-site until tomorrow.

## Debrief

1. How long would we be down? Is that acceptable?
2. When did we last restore from backup, and what did we restore?
3. Which accounts have remote access, and do they all have MFA?

Record it on the [tabletop record](../templates/tabletop-record.md).

## Sources

- [Ransomware Guide](https://www.cisa.gov/stopransomware/ransomware-guide), from CISA: response checklist, backups, and data theft before encryption.
- [Updated advisory on potential sanctions risks for facilitating ransomware payments](https://ofac.treasury.gov/media/912981/download), from the Treasury Department's OFAC: sanctions risk in paying.
- [CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages), from CISA: the exercise format.
