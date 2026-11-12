# There Are No Incidents

**Incident response training for small businesses: a runbook, playbooks, tabletop exercises, and templates.** Everything a small office needs to plan for a security incident, practice it, and handle a real one, in plain language and backed by primary sources.

From [neon1](https://neon1.tech). *1 is glad to be of service.*

---

"There are no incidents here" is usually what an office says right before it finds one. Most small businesses have a few a year: a mailbox someone else signed in to, a laptop left in a cab, an invoice paid to a fraudster's account. This kit is for handling them on purpose.

## Who it's for

- **Owners and office managers** of businesses with 2 to 50 people, especially those holding client financial, tax, or health information.
- **The person who handles IT**, whether on staff or at a managed service provider.
- **Trainers and consultants** who want an open, adaptable kit to run exercises from.

You don't need a security background. You do need someone who will own the plan.

## What's inside

| Folder | What it holds |
|---|---|
| [`runbook/`](runbook/index.md) | The response, step by step: get ready, is this an incident, the first hour, contain, investigate, notify, recover, and learn. |
| [`playbooks/`](playbooks/index.md) | What's different about the six incidents small businesses see most: business email compromise, ransomware, a lost device, a compromised account, a vendor breach, and misdirected data. |
| [`tabletops/`](tabletops/index.md) | A [facilitator guide](tabletops/facilitator-guide.md) and six 60 to 90 minute exercises, one for each playbook, with staged injects, questions, and what good looks like. |
| [`templates/`](templates/index.md) | A one-page response plan, a contact sheet, an incident log, a notification worksheet, an after-action report, and a tabletop record. |
| [`reference/`](reference/notification-rules.md) | [Notification rules](reference/notification-rules.md) (U.S. federal and New York) with deadlines and links to the rule text, and a [glossary](reference/glossary.md). |

## Start here

1. Read the [runbook](runbook/index.md) once, start to finish. It takes about 30 minutes.
2. Fill in the [response plan](templates/response-plan.md) and [contact sheet](templates/contact-sheet.md), and print both.
3. Within a month, run [the wire that wasn't](tabletops/01-the-wire-that-wasnt.md) or [reply all](tabletops/06-reply-all.md) with your team, using the [facilitator guide](tabletops/facilitator-guide.md).
4. Fix the top three gaps it finds, then run a different exercise next year.

If something is happening right now, go to [the first hour](runbook/first-hour.md).

## How it fits with neon1's other guides

- [Ready, Secure, Go](https://github.com/neon1llc/ready-secure-go) is the reference: practice cards, and playbooks for households and individuals when something already went wrong.
- [Phish Out of Water](https://github.com/neon1llc/phish-out-of-water) is a one-hour awareness session. It helps staff spot the scams that start most of the incidents here.
- [SOC It 2 Me](https://github.com/neon1llc/soc-it-2-me) is SOC 2 readiness training. Its incident controls ask for a plan, a log, and a yearly tabletop, which this kit provides.
- [You Have 20 Seconds To Comply](https://github.com/neon1llc/you-have-20-seconds-to-comply) explains the compliance rules, such as HIPAA and the FTC Safeguards Rule, whose notice duties appear in the notification rules here.

Want neon1 to run a tabletop exercise for your team? See [neon1.tech](https://neon1.tech).

## What this isn't

There Are No Incidents is training, not legal advice or an incident response service. Notification duties depend on the facts, the data, and where people live. Decide them with a lawyer. Rules change, so every page that relies on an outside fact lists its sources, and the [notification rules](reference/notification-rules.md) link to each rule's official text. NIST, CISA, the FTC, HHS, and the other sources are described here in our own words. See [ATTRIBUTIONS.md](ATTRIBUTIONS.md).

## Checking a change

```
node tools/check.mjs    # front matter on every page, and no broken links
```

## Licenses

| What | License | What it means |
|---|---|---|
| Written material (everything except `tools/` and `.github/`) | [CC BY-SA 4.0](LICENSE) | Share it, teach from it, adapt it, even commercially. Credit it as *"Based on There Are No Incidents by neon1 (neon1.tech), CC BY-SA 4.0"* and share your changes under the same license. |
| Code (`tools/`, `.github/`) | [MIT](LICENSE-CODE) | Use it for anything, keeping the copyright notice. |
| The There Are No Incidents and neon1 names and the neon1 logo | Reserved | Not covered by either license. See [TRADEMARK.md](TRADEMARK.md). |

There Are No Incidents is © 2026 neon1 LLC. Keep the [NOTICE](NOTICE) file in copies and adaptations.

Found something wrong or outdated? See [SECURITY.md](SECURITY.md). Want to help? See [CONTRIBUTING.md](CONTRIBUTING.md).
