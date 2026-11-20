---
title: Recover
description: "Remove the attacker's foothold, rebuild and restore in priority order, and watch for a return."
---

Start recovery once containment is done and the tech lead can explain how the attacker got in. Restoring sooner often restores the attacker too.

## Clean up

- **Remove every foothold** the investigation found: malware, remote access tools, extra admin accounts, app registrations, forwarding rules, and scheduled tasks.
- **Fix the way in.** Patch the device, turn on MFA, close the exposed port, or end the vendor's access.
- **Reset credentials in reach:** involved and admin accounts, shared passwords, service accounts, API keys, and Wi-Fi passwords if the network was involved.

## Rebuild and restore

1. **Rebuild infected computers** from a clean install, not in place, unless the forensics firm says otherwise.
2. **Check backups before using them.** Restore to an isolated machine and scan the result. Pick a backup from before the first sign of access, using the date from [investigate](investigate.md).
3. **Restore in priority order:** email, phones, the line-of-business system, and payments first.
4. **Confirm each system works** with the person who uses it daily.

## Watch for a return

Watch sign-in logs and alerts for at least 30 days, because attackers often return through a door nobody closed. Warn staff, and clients if their data was exposed, to expect phishing that uses details from the incident, and give clients a way to check that a message came from you.

## Close the incident

The incident lead closes it when systems are restored, notifications are done or scheduled, and nothing suspicious has turned up for an agreed period. Log the closing date and reason in the [incident log](../templates/incident-log.md), then schedule the [review](learn.md).

## Sources

- [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final), from NIST: incident recovery plan execution (RC.RP) and restoring assets in priority order.
- [Ransomware Guide](https://www.cisa.gov/stopransomware/ransomware-guide), from CISA: rebuild from clean images, restore from clean backups, and reset credentials.
- [Contingency planning guide for federal information systems](https://csrc.nist.gov/pubs/sp/800/34/r1/upd1/final), NIST SP 800-34 Rev. 1: recovery priorities and testing restored systems.
