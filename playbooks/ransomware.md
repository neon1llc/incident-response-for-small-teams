---
title: Ransomware
description: "Files are locked and there's a ransom note: isolate, call the insurer, check the backups, and treat it as likely data theft."
---

## First moves

1. **Isolate.** Unplug network cables and turn off Wi-Fi on affected computers, but leave them powered on. If you can't tell what's affected, disconnect the office at the router.
2. **Protect the backups.** Disconnect backup drives and pause cloud sync so they aren't encrypted too.
3. **Call your cyber insurer** before anyone else outside, including the attackers. Policies often require their breach coach, forensics firm, and negotiators.
4. **Photograph the note** and record its wording. It may name the group, which tells responders what to expect. Don't reply to it.

## Checks

- **How did they get in?** Commonly a phished password, exposed remote desktop, unpatched VPN or firewall, or compromised MSP tool. Close it before restoring, or they can walk back in.
- **Was data copied out first?** Most groups steal data before encrypting and threaten to publish it. Look for large uploads in firewall logs and archive tools on servers. If data was copied, or you can't rule it out, treat it as a breach of everything on the affected systems. See [notify](../runbook/notify.md).
- **Are the backups intact?** Test them on an isolated machine first.

## About paying

Don't pay or negotiate yet. Paying is a business and legal decision made with your insurer, lawyer, and responders. The U.S. government strongly discourages it. Payment doesn't guarantee working decryption or deletion of stolen data, and paying a sanctioned group can violate U.S. sanctions law. A DFS-regulated business in New York must also give notice of a ransom payment within 24 hours. See [notification rules](../reference/notification-rules.md).

Report to the FBI at ic3.gov and to CISA at cisa.gov/report. Reports help responders and may surface decryption keys.

## Sources

- [Ransomware Guide](https://www.cisa.gov/stopransomware/ransomware-guide), from CISA: the response checklist, including isolation, backups, and reporting.
- [Internet Crime Complaint Center](https://www.ic3.gov/), from the FBI: reporting ransomware.
- [Report a cyber incident](https://www.cisa.gov/report), from CISA: voluntary incident reporting.
- [Cybersecurity regulation](https://www.dfs.ny.gov/cybersecurity), from the New York Department of Financial Services: the ransom payment notice in 23 NYCRR 500.17.
- [Updated advisory on potential sanctions risks for facilitating ransomware payments](https://ofac.treasury.gov/media/912981/download), from the Treasury Department's OFAC: why a payment can break sanctions law, and why early reporting counts in your favor.
- [Playbook: ransomware in a small office](https://github.com/neon1llc/ready-secure-go/blob/main/content/playbooks/ransomware-small-office.md), in Ready, Secure, Go: the same response in its shortest form.
