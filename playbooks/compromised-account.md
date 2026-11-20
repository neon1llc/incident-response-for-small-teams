---
title: Compromised account
description: "Someone else is signed in to a staff or admin cloud account: lock them out and check what they read."
---

## First moves

From a clean device, with an admin account:

1. **Screenshot first:** inbox rules, forwarding settings, recent sign-ins, registered MFA methods, and connected apps.
2. **Reset the password** (or disable the account for a few hours if work can wait), and give the new one by phone or in person, never email. Then **sign out all sessions**, which also kills stolen sign-in tokens.
3. **Reset MFA.** Remove every method and have the person re-register in person or on a verified call, because attackers often add their own phone or app.
4. **Remove what the attacker added:** forwarding to outside addresses, rules that move or delete mail (some are hidden from Outlook, so have IT list them with admin tools), delegates, and app passwords, which a password reset doesn't revoke.
5. **Disable unknown connected apps, then revoke their consent.** An app that's only deleted can return when someone approves it again.
6. **For an admin account,** also check for new admins, changed settings, and mail flow rules that affect everyone.

## Checks

- **How did they get in?** A phishing page that caught the password and MFA code, a reused password, an MFA prompt approved to make it stop, or a malicious app consent.
- **What did they do?** If logging was on, the audit log shows mail sent, searches for "invoice," "wire," or "W-2," downloads, and shared folders.
- **What could they read?** Years of client email often hold tax documents, IDs, and account numbers. If the audit log shows what was opened, scope notice to that. If not, treat everything the account could reach as exposed. See [notify](../runbook/notify.md).

## Prevent a repeat

Use phishing-resistant MFA (passkeys or security keys), admins first. Block legacy sign-in methods. Alert on new forwarding rules and sign-ins from new countries. Keep at least 90 days of audit logs.

## Sources

- [Responding to a compromised email account](https://learn.microsoft.com/en-us/defender-office-365/responding-to-a-compromised-email-account), from Microsoft: symptoms, hidden inbox rules, app passwords, session revocation, and unblocking a mailbox from sending.
- [Identify and secure compromised accounts](https://knowledge.workspace.google.com/admin/support/troubleshooting/identify-and-secure-compromised-accounts), from Google: the same steps for Google Workspace.
- [App consent grant investigation](https://learn.microsoft.com/en-us/security/compass/incident-response-playbook-app-consent), from Microsoft: finding malicious app consents, and disabling an app before revoking it.
- [Secure Cloud Business Applications (SCuBA)](https://www.cisa.gov/resources-tools/services/secure-cloud-business-applications-scuba-project), from CISA: secure settings, logging, and alerting for Microsoft 365 and Google Workspace.
- [Implementing phishing-resistant MFA](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf), from CISA: why codes and push prompts can be phished, and what can't be.
- [Business email compromise](https://www.fbi.gov/how-we-can-help-you/scams-and-safety/common-frauds-and-scams/business-email-compromise), from the FBI: how compromised mailboxes are used for payment fraud.
