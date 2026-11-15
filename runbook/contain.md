---
title: Contain
description: "Cut off the attacker's access and stop the spread without destroying the evidence you'll need to decide who to notify."
---

Containment balances stopping harm fast against keeping the evidence of what happened. Without evidence you can't show that data *wasn't* taken, and some notification rules then presume it was. When the two conflict, stop money and ongoing harm first, and preserve evidence second.

## Short-term containment

Do these in the first hours, from a trusted device.

| If | Do | Don't |
|---|---|---|
| An email or cloud account is compromised | Reset the password, sign out all sessions, re-register multifactor authentication (MFA), and remove forwarding rules, inbox rules, unknown devices, and connected apps | Delete the account or the attacker's rules before they're recorded. Screenshot them first |
| An admin account is compromised | Do the above, then check for new admin accounts, changed MFA settings, and new app registrations | Assume one password reset is enough |
| A computer shows ransomware or malware | Disconnect it from the network, cable and Wi-Fi, and leave it on | Power it off, wipe it, or run cleanup tools before the tech lead says so |
| Several computers are affected, or you can't tell | Disconnect the office from the internet at the router, then reconnect clean machines one at a time | Let people keep working "until it's sorted" |
| A device is lost or stolen | Lock or wipe it remotely, and revoke its sessions and saved passwords | Wait to see if it turns up |
| A vendor is breached | Rotate any passwords, keys, and tokens you share with them, and limit their access until they explain | Wait for their press release |
| Data was sent to the wrong place | Ask the recipient to delete it and confirm in writing, and recall or expire the message or share link | Ignore it because "it was only one person" |

## Keep evidence while you contain

- **Write down every action** in the [incident log](../templates/incident-log.md) with the time and who did it, including what you changed.
- **Screenshot before you change**: inbox rules, sign-in alerts, ransom notes, and admin settings.
- **Export logs early.** Many small-business plans keep sign-in and audit logs for only weeks. Export them before they roll off. See [investigate](investigate.md).
- **Keep affected devices** as they are, powered on and disconnected, until the forensics firm or IT provider says otherwise.

## Long-term containment

Once the immediate threat is cut off, keep the business running during the investigation:

- Move people to known-clean devices or temporary accounts.
- Block the attacker's known addresses, domains, and file names at the firewall and email filter.
- Require MFA everywhere it isn't yet, starting with email and admin accounts.
- Keep watching sign-in logs. Attackers who lose one way in often try another within days.

Containment is done when the tech lead can say how the attacker got in and that every known way in is closed. Until then, the incident is active.

## Sources

- [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final), from NIST: incident mitigation (RS.MI) and the tradeoff between containment and evidence.
- [Ransomware Guide](https://www.cisa.gov/stopransomware/ransomware-guide), from CISA: isolating systems, keeping them powered on, and resetting credentials.
- [Data Breach Response: A Guide for Business](https://www.ftc.gov/business-guidance/resources/data-breach-response-guide-business), from the FTC: stop additional data loss and don't destroy evidence.
- [45 CFR 164 Subpart D](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-D), HIPAA Breach Notification Rule: a breach is presumed unless a risk assessment shows a low probability that data was compromised.
- [16 CFR 314.2](https://www.ecfr.gov/current/title-16/section-314.2), FTC Safeguards Rule: unauthorized access is presumed to include acquisition unless you have reliable evidence it didn't.
