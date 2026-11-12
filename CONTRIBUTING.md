# Contributing

Rules and deadlines change, and every office's setup is a little different, so corrections and real-world detail help most.

## What helps most

- Corrections to a deadline, agency, or reporting address, with a link to the official rule or agency page.
- Notification rules for other states or industries, written in the same table format and linked to the rule text.
- New tabletop exercises or injects drawn from incidents you've handled, with every name, number, and identifying detail removed or changed.
- Notes on running the exercises with a particular kind of team, such as a clinic, a law office, or a nonprofit.
- Accessibility fixes and translations.

## How to write here

- **Write for the person in the middle of it.** Short steps, plain words, and the action first.
- **Cite the rule, not a summary of it.** Every outside fact gets a Sources entry linking the official text or agency page.
- **Say what's uncertain.** Deadlines and definitions vary by law. Don't round them into something simpler than the rule says.
- **No fear selling.** Say what the risk is and what to do about it.
- **Never include real client data, working malicious links, or real phone numbers** in an exercise. Use `example.com` addresses and 555 numbers.
- Use the serial comma.

## Checking your change

```
node tools/check.mjs
```

## Branches and commits

Name branches `feat/`, `fix/`, `docs/`, or `chore/` plus a short hyphenated description. Use [Conventional Commits](https://www.conventionalcommits.org/), for example `feat(tabletops): add a payroll diversion exercise` or `fix(reference): correct the HIPAA media notice threshold`. Merge with `git merge --no-ff`, and never rewrite history on `main`.
