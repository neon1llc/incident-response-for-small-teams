# Changelog

Incident Response for Small Teams releases use `v0.MINOR.PATCH` until the first complete release, v1.0.0, following neon1's [versioning standard](https://neon1.tech/knowledge/standards/versioning/). Each version below has an annotated tag on the commit it names; the release workflow adds missing tags and never moves one.

## v0.1.4 - 2026-11-19

### Changed
- Removed the claim about how many incidents small businesses see a year, and the description of the kit as complete. The README, runbook, and playbooks say to adapt the material to your own plan and providers.
- Added a starting path for teams that already have a response plan.

## v0.1.3 - 2026-11-19

### Changed
- The FTC Safeguards Rule's written-plan requirement is described with its exemption below 5,000 consumers.
- HIPAA rows say "without unreasonable delay and within 60 days". Regulation S-P compliance dates and a New York section 899-bb line were added.
- The notification reference says to call your lawyer and cyber insurer first.
- The business email compromise playbook adds SPF, DKIM, and DMARC. The ransomware playbook adds the U.S. government's position on paying.
- "Proof" is "evidence" where it overstated, and a dead FTC link was fixed.

## v0.1.2 - 2026-11-15

### Changed
- Shorter, plainer wording in the README, runbook, playbooks, and tabletop guides.

## v0.1.1 - 2026-11-13

### Changed
- The project is now called Incident Response for Small Teams, in the README, LICENSE, NOTICE, TRADEMARK.md, attributions, and templates. The credit line in LICENSE and NOTICE uses the new name.
- Notification guidance says that requirements vary by jurisdiction, sector, and contract, that a lawyer decides what applies, and that each deadline is an example from the rule named beside it. The notification worksheet says the same above its table.
- The README says the scope is stable: the repository gets accuracy and source updates, and no new modules for now.

### Fixed
- The contracts section no longer gives a typical contract notice window without a source. It points to each contract's own wording.
- The worksheet's Regulation S-P deadline counts 30 days from becoming aware, as the rule does.

## v0.1.0 - 2026-11-12

### Added
- A runbook: get ready, is this an incident (with four severity levels), the first hour, contain, investigate, notify, recover, and learn, mapped to NIST SP 800-61 Rev. 3 and the CSF 2.0 functions.
- Six playbooks: business email compromise, ransomware, lost or stolen device, compromised account, vendor breach, and misdirected data.
- A facilitator guide and six tabletop exercises, one per playbook, each with staged injects, questions, what good looks like, curveballs, and a debrief.
- Templates: a one-page response plan, contact sheet, incident log, notification worksheet, after-action report, and tabletop record.
- Notification rules for U.S. federal and New York requirements, linked to each rule's text, and a glossary.
