---
title: Business email compromise
description: "A payment went to a fraudster after an email asked for new bank details, or a mailbox was used to send fake invoices."
---

**Signs:** a supplier says they never got paid, a client asks why your invoice has new bank details, an employee asks why the owner wanted gift cards, or a payroll deposit went to a new account.

## First moves

1. **Call your bank's fraud line now** and ask for a recall of the wire or ACH payment. Give them the amount, date, and receiving account. Ask them to contact the receiving bank.
2. **Report it at ic3.gov** the same day, with the transaction details. The FBI uses these reports to try to freeze stolen funds, and the chance of getting money back drops with each day.
3. **Find out whose mailbox was used.** It may be yours, the supplier's, or a look-alike domain one letter off. Each leads somewhere different:
   - **Yours:** follow [compromised account](compromised-account.md).
   - **Theirs:** call them on a number you already had, and tell them their account may be compromised.
   - **A look-alike:** record the domain, and report it to the registrar and your email filter.

## Checks

- Search all mailboxes for other messages from the same sender, domain, or with the same bank details. Other staff may have received them.
- Check inbox and forwarding rules in every mailbox involved. Attackers hide replies by moving them to folders like RSS Subscriptions, Junk Email, or Archive.
- Check whether the attacker could read client data in the mailbox. That changes this from a fraud into a possible breach.

## Notification questions

- Did the attacker get into a mailbox that holds personal information? If so, work through [notify](../runbook/notify.md).
- Were clients sent fake invoices from your account? Tell them, by phone or a channel other than the compromised email, how to check a payment request is real.

## Prevent the next one

Make "any change to where money goes gets a callback to a number already on file" a written rule with no exceptions. Require MFA on every mailbox. Have your IT provider set up SPF, DKIM, and DMARC for your domain, so it's harder to spoof. Ask your bank about payee verification and dual approval for new payees.

Ready, Secure, Go has the practice card: [Never change payment details on the strength of an email](https://github.com/neon1llc/ready-secure-go/blob/main/content/practices/scams-and-social-engineering/scam-payment-change-verification.md).

## Sources

- [Business email compromise](https://www.fbi.gov/how-we-can-help-you/scams-and-safety/common-frauds-and-scams/business-email-compromise), from the FBI: invoice, bank change, and payroll fraud, and calling the bank and IC3 at once.
- [Internet Crime Complaint Center](https://www.ic3.gov/), from the FBI: reporting, and fast reports that sometimes let the FBI freeze funds.
- [2025 Internet Crime Report](https://www.ic3.gov/AnnualReport/Reports/2025_IC3Report.pdf), from the FBI IC3: ask your bank to recall the funds right away, and file at ic3.gov whatever the amount, so the Recovery Asset Team can try to freeze them.
- [Cybersecurity for small business](https://www.ftc.gov/business-guidance/small-businesses/cybersecurity), from the FTC: business email imposters, look-alike domains, and SPF, DKIM, and DMARC.
