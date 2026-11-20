---
title: The first hour
description: "What to do in the first 60 minutes after someone reports something wrong: declare, assign, stop the money, contain, call, and write it all down."
---

Print this page.

## Minute 0 to 10: take the report

1. **Write down what the reporter saw,** when, and on which device or account. Ask them not to touch anything else.
2. **Ask the four questions** from [is this an incident?](is-this-an-incident.md): is money moving, could someone be in our systems now, could personal data be involved, can we still work?
3. **Set a severity level.** When unsure, pick the higher one.

## Minute 10 to 20: declare and assign

4. **Declare it out loud,** by call or text on your backup channel, not email. For example: "This is a level 2 incident. I'm leading. Dana is scribe, Sam is tech lead. We'll talk again at 10:30."
   Give it a plain two-word codename, such as "Blue Kettle," for file names, chats, and calendar holds. It keeps "breach" out of messages before anyone knows that's what it is.
5. **Name the roles:** tech lead, scribe, and communications. The scribe opens the [incident log](../templates/incident-log.md) now and backfills the first 20 minutes.
6. **Set the next check-in,** about every 30 minutes at first. Between check-ins, let people work.
   Don't debate severity or process now. Act on the higher level and raise disagreements at the [review](learn.md).

## Minute 20 to 40: stop the damage

7. **If money moved, call the bank first.** Ask its fraud department to recall or freeze the transfer, and report it at **ic3.gov**. Fast reports give wire transfers the best chance of coming back.
8. **Contain what you can see,** following [contain](contain.md):
   - A compromised account: reset its password from a clean device, sign it out everywhere, and remove unknown devices, forwarding rules, and app connections.
   - An infected computer: unplug the network cable and turn off Wi-Fi. **Leave it powered on.** Memory holds evidence.
   - A lost device: lock or wipe it remotely and revoke its sessions.
9. **Don't delete, reimage, pay, or contact the attacker.** Each destroys evidence or options.

## Minute 40 to 60: call for help

10. **Call your IT provider's** after-hours line if they aren't already on it.
11. **For level 1 or 2, call your cyber insurer's** claim line. Many policies require notice within a set time and will assign a breach coach, lawyer, and forensics firm. Ask before hiring anyone yourself.
12. **Call a lawyer** if personal information may be involved. Notification clocks may already be running. See [notify](notify.md).
13. **Tell staff only what they need:** what to avoid (such as "don't open email until further notice"), how to reach the lead, and not to discuss it outside the company or on social media.

## At the one-hour mark

The lead checks with each role and writes in the log:

- What we know and don't.
- What's contained and what isn't.
- Who's been called and who still needs to be.
- The severity level now and the next check-in.

Then move on to [contain](contain.md) and [investigate](investigate.md), and open the matching [playbook](../playbooks/index.md).

## Sources

- [Ransomware Guide](https://www.cisa.gov/stopransomware/ransomware-guide), from CISA: isolate affected systems, keep them powered on, and use out-of-band communication.
- [Business email compromise](https://www.fbi.gov/how-we-can-help-you/scams-and-safety/common-frauds-and-scams/business-email-compromise), from the FBI: call the bank and report to IC3 at once after a fraudulent transfer.
- [Internet Crime Complaint Center](https://www.ic3.gov/), from the FBI: where to report, and why speed matters for recovering funds.
- [Data Breach Response: A Guide for Business](https://www.ftc.gov/business-guidance/resources/data-breach-response-guide-business), from the FTC: secure operations, assemble a team, and preserve evidence.
