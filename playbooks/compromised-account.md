---
title: Compromised account
description: "Someone else is signed in to a staff or admin account in Microsoft 365, Google Workspace, or another cloud app: lock them out, find what they did, and check what they could read."
---

**Signs:** a mailbox suddenly blocked from sending, sign-in alerts from unfamiliar places, MFA prompts nobody asked for, contacts getting odd emails from a staff address, missing or auto-deleted messages, or a new forwarding rule.

## First moves

From a clean device, with an admin account:

1. **Screenshot first:** the account's inbox rules, forwarding settings, recent sign-ins, registered MFA methods, and connected apps.
2. **Disable the account** for a few hours if the work can wait. If not, **reset the password**, and give the new one by phone or in person, never by email. Then **sign out all sessions**, which also invalidates stolen sign-in tokens.
3. **Reset MFA.** Remove every registered method and have the person register again, in person or on a verified call. Attackers often add their own phone or app.
4. **Remove what the attacker added:** forwarding to outside addresses, inbox rules that move or delete mail (some are hidden from Outlook, so have your IT provider list them with admin tools), delegates, and app passwords, which a password reset doesn't revoke.
5. **Disable unknown connected apps, then revoke their consent.** An app that's only deleted can come back the next time someone approves it.
6. **If it's an admin account**, check for new admin accounts, changed security settings, new app registrations, and mail flow rules that affect everyone.

## Checks

- **How did they get in?** A phishing page that captured the password and MFA code, a password reused from another breach, an MFA prompt someone approved to make it stop, or a malicious app consent.
- **What did they do?** Sent mail, searched for words like "invoice," "wire," or "W-2," downloaded files, or shared folders. The audit log shows mail and file access if logging was on.
- **Did it spread?** Other accounts signing in from the same addresses, or phishing sent from this account to colleagues and clients.

## Notification questions

The mailbox is the issue. Years of client email often hold tax documents, IDs, account numbers, and health information. If the audit log shows what was opened, scope notice to that. If it doesn't, plan on treating everything the account could reach as exposed, and work through [notify](../runbook/notify.md).

## Prevent the next one

Phishing-resistant MFA (passkeys or security keys) for admins first, then everyone. Block legacy sign-in methods. Alert on new forwarding rules and sign-ins from new countries. Keep at least 90 days of audit logs.

## Sources

- [Responding to a compromised email account](https://learn.microsoft.com/en-us/defender-office-365/responding-to-a-compromised-email-account), from Microsoft: symptoms, hidden inbox rules, app passwords, session revocation, and unblocking a mailbox from sending.
- [Identify and secure compromised accounts](https://knowledge.workspace.google.com/admin/support/troubleshooting/identify-and-secure-compromised-accounts), from Google: the same steps for Google Workspace.
- [App consent grant investigation](https://learn.microsoft.com/en-us/security/compass/incident-response-playbook-app-consent), from Microsoft: finding malicious app consents, and disabling an app before revoking it.
- [Secure Cloud Business Applications (SCuBA)](https://www.cisa.gov/resources-tools/services/secure-cloud-business-applications-scuba-project), from CISA: secure settings, logging, and alerting for Microsoft 365 and Google Workspace.
- [Implementing phishing-resistant MFA](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf), from CISA: why codes and push prompts can be phished, and what can't be.
- [Business email compromise](https://www.fbi.gov/how-we-can-help-you/scams-and-safety/common-frauds-and-scams/business-email-compromise), from the FBI: how compromised mailboxes are used for payment fraud.
