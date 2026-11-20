---
title: Contain
description: "Cut off the attacker's access without destroying the evidence you'll need to decide who to notify."
---

Stopping harm fast and keeping evidence can conflict. Without evidence you can't show that data *wasn't* taken, and some notification rules then presume it was. Stop money and ongoing harm first, and preserve evidence second.

## Short-term containment

Do these in the first hours, from a trusted device. For a lost device, a vendor breach, or data sent to the wrong place, see the [playbooks](../playbooks/index.md).

| If | Do |
|---|---|
| An email or cloud account is compromised | Reset the password, sign out all sessions, re-register multifactor authentication (MFA), and remove forwarding rules, inbox rules, unknown devices, and connected apps. Don't delete the attacker's rules before they're recorded |
| An admin account is compromised | Do the above, then check for new admin accounts, changed MFA settings, and new app registrations. One password reset isn't enough |
| A computer shows ransomware or malware | Disconnect it from the network, cable and Wi-Fi, and leave it on. Don't power it off, wipe it, or run cleanup tools before the tech lead says so |
| Several computers are affected, or you can't tell | Disconnect the office at the router, then reconnect clean machines one at a time |

**Keep evidence while you contain:**

- **Log every action** in the [incident log](../templates/incident-log.md) with the time and who did it.
- **Screenshot before you change:** inbox rules, sign-in alerts, ransom notes, and admin settings.
- **Export logs early.** Many small-business plans keep them for only weeks.
- **Keep affected devices** powered on and disconnected until forensics or IT says otherwise.

Once the immediate threat is cut off, move people to known-clean devices or temporary accounts, block the attacker's known addresses, domains, and file names, require MFA everywhere, and watch sign-in logs, because attackers who lose one way in often try another within days. Containment is done when the tech lead can say how the attacker got in and that every known way in is closed.

## Sources

- [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final), from NIST: incident mitigation (RS.MI) and the tradeoff between containment and evidence.
- [Ransomware Guide](https://www.cisa.gov/stopransomware/ransomware-guide), from CISA: isolating systems, keeping them powered on, and resetting credentials.
- [Data Breach Response: A Guide for Business](https://www.ftc.gov/business-guidance/resources/data-breach-response-guide-business), from the FTC: stop additional data loss and don't destroy evidence.
- [45 CFR 164 Subpart D](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-D), HIPAA Breach Notification Rule: a breach is presumed unless a risk assessment shows a low probability that data was compromised.
- [16 CFR 314.2](https://www.ecfr.gov/current/title-16/section-314.2), FTC Safeguards Rule: unauthorized access is presumed to include acquisition unless you have reliable evidence it didn't.
