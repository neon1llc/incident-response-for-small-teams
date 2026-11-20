---
title: Lost or stolen device
description: "A device with work data is missing: lock or wipe it, cut its access, and find out whether the data was protected."
---

## First moves

1. **Get the facts:** which device, when and where it was last seen, whether it was locked, and what it could open.
2. **Lock or wipe it** with your device management tool or the owner's Apple, Google, or Microsoft account. Lock if there's a real chance of getting it back. Otherwise wipe.
3. **Cut its access.** Sign it out of email and cloud apps from the admin center, revoke sessions and app passwords, and change passwords saved on it.
4. **Report theft to the police** and keep the report number. Insurers usually ask for it.

## The question that decides everything

**Was the device encrypted, with a strong passcode, and locked when it was lost?** Full-disk encryption (FileVault, BitLocker, or a modern phone with a passcode) usually means the data is unreadable. Most notification laws, including New York's and the FTC Safeguards Rule, apply to *unencrypted* information. HIPAA doesn't count properly encrypted health data as unsecured.

Prove it. Your device management tool or IT provider can usually show that encryption was on and when the device last checked in. Save that record in the [incident log](../templates/incident-log.md).

- **Encrypted, locked, and the key wasn't with it:** usually not a breach. Record why and keep the evidence.
- **Not encrypted, or you can't show it was:** list what was stored or synced on it, and work through [notify](../runbook/notify.md).
- **Paper files lost with it:** paper counts under HIPAA and some state laws, though not New York's law for computerized data.

## Sources

- [New York General Business Law § 899-aa](https://www.nysenate.gov/legislation/laws/GBS/899-AA), from the New York State Senate: the law covers computerized data and treats encrypted data as exposed only if the key was too.
- [16 CFR 314.2](https://www.ecfr.gov/current/title-16/section-314.2), FTC Safeguards Rule: a notification event involves unencrypted customer information, or encrypted information whose key was taken.
- [Breach Notification Rule](https://www.hhs.gov/hipaa/for-professionals/breach-notification/index.html), from HHS: encrypted health information isn't "unsecured," and paper records are covered.
- [How to protect your phone and the data on it](https://consumer.ftc.gov/articles/how-protect-your-phone-and-data-it), from the FTC: locking, encrypting, and remote wiping.
