# David Purvis

Software engineer in Broomfield, CO. MS Computer Science at CU Boulder (2026–2028);
BS Computer Science from Mississippi State, summa cum laude. Before grad school I was
the sole Salesforce administrator for the City of Aspen — ~110 staff licenses, ~10,000
users — building integrations against Oracle Financials that moved millions of dollars
a month.

Looking for platform, infrastructure, and SRE work.

### How I build

Most of what's below was built with an AI coding agent, with me as the engineer
directing it: I write the requirements, make the architecture calls, review the
diffs, decide what gets tested, and own what ships. The commit history is unedited,
so you can see exactly how that went — including the parts that took six rebuilds.

### Projects

**[cs2-utility-playbook](https://github.com/DavidPurvis/cs2-utility-playbook)** —
TypeScript · Vite · Playwright · GitHub Actions · [live site](https://davidpurvis.github.io/cs2-utility-playbook/)

A team-execute reference app for Counter-Strike 2 — say "scenario 4" and everyone is
on the same page. The parts I care about: a single `npm run validate` gate (typecheck,
lint, unit + E2E tests, data-integrity checks, build); CLI generators that turn raw
in-game coordinates into validated entries in a typed dataset; Playwright end-to-end
tests with visual snapshots; CI and GitHub Pages deploys; and a `docs/` folder holding
the requirements, solution design, and decision ledger I wrote to keep the build honest.

**[River_Permit_Tracker](https://github.com/DavidPurvis/River_Permit_Tracker)** — Python

Polls recreation.gov for Green River (Gates of Lodore) permit openings and sends
Discord or email notifications when dates appear. Runs unattended on a schedule with
rotating logs. Permits there are scarce and go fast, so the useful part is noticing
before a human would.

**[River-Gauge-Web-App](https://github.com/DavidPurvis/River-Gauge-Web-App)** — Python · Flask

Real-time river flow (CFS) for runs near Glenwood Springs, CO. Replaced a physical
whiteboard that went stale for days — which matters when a 100 CFS swing changes the
features on the river.

**[pulsar-battery-controller](https://github.com/DavidPurvis/pulsar-battery-controller)** ·
**[streamcontroller-styled-widgets](https://github.com/DavidPurvis/streamcontroller-styled-widgets)** — Python

Two StreamController plugins: Pulsar X3 Mini mouse battery and DPI over HID, with a
Flatpak-safe host adapter and a shared polling cache; and matching Weather, Clock,
and Date widgets under one high-contrast visual system.

### Background

City of Aspen, 2024–2026: IT Support Specialist, then sole Salesforce administrator
and integration developer — Apex, Flows, REST, and Python against Oracle Financials.
Mostly Python and Linux. Three seasons guiding whitewater in Glenwood Springs.

davidpurvis647@gmail.com · [LinkedIn](https://linkedin.com/in/dgp0)
