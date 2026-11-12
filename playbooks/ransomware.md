---
title: Ransomware
description: "Files are locked and there's a ransom note: isolate, call the insurer before anyone else outside, check the backups, and treat it as a likely data theft too."
---

**Signs:** files that won't open or have strange extensions, a ransom note on screens or in folders, everything suddenly slow, or antivirus alerts on several machines at once.

## First moves

1. **Isolate.** Unplug network cables and turn off Wi-Fi on affected computers, and leave them powered on. If you can't tell what's affected, disconnect the office at the router.
2. **Protect the backups.** Disconnect backup drives and pause sync to cloud storage so the backups don't get encrypted too.
3. **Call your cyber insurer** before contacting anyone else outside, including the attackers. Policies often require using their breach coach, forensics firm, and negotiators.
4. **Don't pay, negotiate, or reply** to the ransom note. That decision belongs to the incident lead with the insurer and lawyer, later.
5. **Photograph the ransom note** and record its exact wording. It may name the group, which tells responders what to expect.

## Checks

- **How did they get in?** Common ways are a phished password, exposed remote desktop, an unpatched VPN or firewall, or a compromised MSP tool. Close that way in before restoring, or the attacker can walk back in.
- **Was data copied out first?** Most ransomware groups now steal data before encrypting it and threaten to publish it. Look for large uploads in firewall logs and archive tools on servers.
- **Are the backups intact?** Check them on an isolated machine before relying on them.

## About paying

Paying is a business and legal decision made with your insurer, lawyer, and responders. Payment doesn't guarantee working decryption or deletion of stolen data, and paying a sanctioned group can violate U.S. sanctions law. If you're a DFS-regulated business in New York, a ransom payment has its own 24-hour notice. See [notification rules](../reference/notification-rules.md).

## Notification questions

If data was copied out, or you can't rule it out, treat it as a breach of everything on the affected systems. Work through [notify](../runbook/notify.md). Report to the FBI through ic3.gov and to CISA at cisa.gov/report. Reports help responders and may surface decryption keys.

## Prevent the next one

Offline or immutable backups restored every quarter, MFA on email and every remote access tool, prompt patching of internet-facing devices, and no remote desktop open to the internet.

## Sources

- [Ransomware Guide](https://www.cisa.gov/stopransomware/ransomware-guide), from CISA: the response checklist, including isolation, backups, and reporting.
- [Internet Crime Complaint Center](https://www.ic3.gov/), from the FBI: reporting ransomware.
- [Report a cyber incident](https://www.cisa.gov/report), from CISA: voluntary incident reporting.
- [Cybersecurity regulation](https://www.dfs.ny.gov/cybersecurity), from the New York Department of Financial Services: the ransom payment notice in 23 NYCRR 500.17.
- [Updated advisory on potential sanctions risks for facilitating ransomware payments](https://ofac.treasury.gov/media/912981/download), from the Treasury Department's OFAC: why a payment can break sanctions law, and why early reporting counts in your favor.
- [Playbook: ransomware in a small office](https://github.com/neon1llc/ready-secure-go/blob/main/content/playbooks/ransomware-small-office.md), in Ready, Secure, Go: the same response in its shortest form.
