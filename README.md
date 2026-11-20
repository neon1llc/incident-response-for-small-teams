# Incident response for small teams

**Incident response preparation for small teams: a runbook, playbooks, tabletop exercises, and templates.** Adapt it to your systems, who is responsible, any response arrangements you already have, and your legal requirements. It cites primary sources.

From [neon1](https://neon1.tech).

**Status:** stable. Accuracy and source updates only, no new modules for now.

---

Use it to rehearse a specific risk, review a response plan, or settle how you work with an IT or security provider.

## Who it's for

- **Owners and office managers** of businesses with 2 to 50 people, especially those holding client financial, tax, or health information.
- **The person who handles IT**, whether on staff or at a managed service provider.
- **Trainers and consultants** who want an open kit to run exercises from.

You don't need a security background, but someone has to own the plan. If you already have one, start with the tabletop exercises and use what they find to review your controls and escalation paths.

## What's inside

| Folder | What it holds |
|---|---|
| [`runbook/`](runbook/index.md) | The response, step by step: get ready, is this an incident, the first hour, contain, investigate, notify, recover, and learn. |
| [`playbooks/`](playbooks/index.md) | Six incident types: business email compromise, ransomware, a lost device, a compromised account, a vendor breach, and misdirected data. |
| [`tabletops/`](tabletops/index.md) | A [facilitator guide](tabletops/facilitator-guide.md) and six 60 to 90 minute exercises, one for each playbook, with staged injects, questions, and what good looks like. |
| [`templates/`](templates/index.md) | A one-page response plan, a contact sheet, an incident log, a notification worksheet, an after-action report, and a tabletop record. |
| [`reference/`](reference/notification-rules.md) | [Notification rules](reference/notification-rules.md) (U.S. federal and New York) with deadlines and links to the rule text, and a [glossary](reference/glossary.md). |

## Start here

1. Read the [runbook](runbook/index.md) once, start to finish, in about 30 minutes.
2. Fill in the [response plan](templates/response-plan.md) and [contact sheet](templates/contact-sheet.md), and print both.
3. Within a month, run [the wire that wasn't](tabletops/01-the-wire-that-wasnt.md) or [reply all](tabletops/06-reply-all.md) with your team, using the [facilitator guide](tabletops/facilitator-guide.md).
4. Fix the top three gaps it finds, then run a different exercise next year.

If something is happening right now, go to [the first hour](runbook/first-hour.md).

## Related

- [Ready, Secure, Go](https://github.com/neon1llc/ready-secure-go): practice cards, and playbooks for households and individuals.
- [Phishing Awareness Kit](https://github.com/neon1llc/phishing-awareness-kit): a one-hour session on the scams that start most of these incidents.
- [SOC 2 Readiness](https://github.com/neon1llc/soc-2-readiness): its incident controls ask for a plan, a log, and a yearly tabletop, which this kit provides.
- [Compliance Basics](https://github.com/neon1llc/compliance-basics): the rules behind the notice duties in the notification rules here, such as HIPAA and the FTC Safeguards Rule.

## What this isn't

This is training, not legal advice or an incident response service. Notification duties vary by jurisdiction, sector, and contract, and depend on the facts and the data, so decide them with a lawyer. Deadlines here are examples, each with the law or rule it comes from named. Rules change, so every page that relies on an outside fact lists its sources, and the [notification rules](reference/notification-rules.md) link to each rule's official text. NIST, CISA, the FTC, HHS, and the other sources are described in our own words. See [ATTRIBUTIONS.md](ATTRIBUTIONS.md).

## Checking a change

```
node tools/check.mjs    # front matter on every page, and no broken links
```

## Licenses

| What | License | What it means |
|---|---|---|
| Written material (everything except `tools/` and `.github/`) | [CC BY-SA 4.0](LICENSE) | Share it, teach from it, adapt it, even commercially. Credit it as *"Based on Incident Response for Small Teams by neon1 (neon1.tech), CC BY-SA 4.0"* and share your changes under the same license. |
| Code (`tools/`, `.github/`) | [MIT](LICENSE-CODE) | Use it for anything, keeping the copyright notice. |
| The Incident Response for Small Teams and neon1 names and the neon1 logo | Reserved | Not covered by either license. See [TRADEMARK.md](TRADEMARK.md). |

Incident Response for Small Teams is © 2026 neon1 LLC. Keep the [NOTICE](NOTICE) file in copies and adaptations.

Found something wrong or outdated? See [SECURITY.md](SECURITY.md). Want to help? See [CONTRIBUTING.md](CONTRIBUTING.md).
