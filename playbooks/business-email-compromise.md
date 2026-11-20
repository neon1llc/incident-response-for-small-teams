---
title: Business email compromise
description: "A payment went to a fraudster after an email about new bank details, or a mailbox sent fake invoices."
---

## First moves

1. **Call your bank's fraud line now** and ask for a recall of the wire or ACH payment, giving the amount, date, and receiving account. Report it at ic3.gov the same day, because the odds of recovery drop each day.
2. **Find out whose mailbox was used.** If yours, follow [compromised account](compromised-account.md). If the supplier's, call them on a number you already had. If a look-alike domain one letter off, report it to the registrar and your email filter.

## Checks

- Search all mailboxes for other messages from the same sender, domain, or bank details.
- Check inbox and forwarding rules in every mailbox involved. Attackers hide replies in folders like RSS Subscriptions, Junk Email, or Archive.
- If the attacker could read client data, see [notify](../runbook/notify.md). If clients got fake invoices from your account, tell them by phone.

## Prevent a repeat

Write a rule with no exceptions: any change to where money goes gets a callback to a number already on file. Require MFA on every mailbox, have IT set up SPF, DKIM, and DMARC, and ask your bank about payee verification and dual approval for new payees. Ready, Secure, Go has the practice card: [Never change payment details on the strength of an email](https://github.com/neon1llc/ready-secure-go/blob/main/content/practices/scams-and-social-engineering/scam-payment-change-verification.md).

## Sources

- [Business email compromise](https://www.fbi.gov/how-we-can-help-you/scams-and-safety/common-frauds-and-scams/business-email-compromise), from the FBI: invoice, bank change, and payroll fraud, and calling the bank and IC3 at once.
- [Internet Crime Complaint Center](https://www.ic3.gov/), from the FBI: reporting, and fast reports that sometimes let the FBI freeze funds.
- [2025 Internet Crime Report](https://www.ic3.gov/AnnualReport/Reports/2025_IC3Report.pdf), from the FBI IC3: ask your bank to recall the funds right away, and file at ic3.gov whatever the amount, so the Recovery Asset Team can try to freeze them.
- [Cybersecurity for small business](https://www.ftc.gov/business-guidance/small-businesses/cybersecurity), from the FTC: business email imposters, look-alike domains, and SPF, DKIM, and DMARC.
