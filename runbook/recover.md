---
title: Recover
description: "Get back to normal safely: remove the attacker's foothold, rebuild and restore in priority order, and watch for a return."
---

Recovery starts once containment is done and the tech lead can explain how the attacker got in. Restoring before that point often restores the attacker too.

## Clean up

- **Remove every foothold** the investigation found: malware, remote access tools, extra admin accounts, app registrations, forwarding rules, and scheduled tasks.
- **Fix the way in.** Patch the device, turn on MFA, close the exposed port, or end the vendor's access.
- **Reset credentials** that were in reach: the accounts involved, admin accounts, shared passwords, service accounts, API keys, and Wi-Fi passwords if the network was involved.

## Rebuild and restore

1. **Rebuild infected computers** from a clean install rather than cleaning them in place, unless the forensics firm says otherwise.
2. **Check backups before using them.** Restore to an isolated machine first and scan the result. Pick a backup from before the first sign of access, using the date from [investigate](investigate.md).
3. **Bring systems back in priority order.** List what the business needs first (email, phones, the line-of-business system, payments) and restore those, then the rest.
4. **Confirm each system works** with the person who uses it every day before calling it done.

## Watch for a return

- Watch sign-in logs and alerts closely for at least 30 days. Attackers often come back through a door nobody closed.
- Tell staff to expect follow-up phishing that uses details from the incident.
- If client data was exposed, expect calls and phishing aimed at clients. Give them a way to check that a message came from you.

## Close the incident

The incident lead closes it when systems are restored, notifications are done or scheduled, and nothing suspicious has turned up for an agreed period. Write the closing date and reason in the [incident log](../templates/incident-log.md), then schedule the review in [learn](learn.md).

## Sources

- [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final), from NIST: incident recovery plan execution (RC.RP) and restoring assets in priority order.
- [Ransomware Guide](https://www.cisa.gov/stopransomware/ransomware-guide), from CISA: rebuild from clean images, restore from clean backups, and reset credentials.
- [Contingency planning guide for federal information systems](https://csrc.nist.gov/pubs/sp/800/34/r1/upd1/final), NIST SP 800-34 Rev. 1: recovery priorities and testing restored systems.
