# David Purvis

Software engineer based in Starkville, MS. I mostly build small, practical tools that solve a
problem I actually have — river gauges I kept checking manually, permits that sell out before I
notice, a keyboard I wanted better battery readouts for.

[LinkedIn](https://www.linkedin.com/in/dgp0/)

---

## Dust 2 Playbook

**[cs2-utility-playbook](https://github.com/DavidPurvis/cs2-utility-playbook)** ·
[live site](https://davidpurvis.github.io/cs2-utility-playbook/) · TypeScript · Vite

A reference app for coordinated team utility executes in Counter-Strike 2, built so that saying
"let's run scenario 4" puts a whole team on the same page. Models three concepts — scenarios
(numbered team executes), lineups (individual throws, shown as a Position → Aim → Throw → Result
walkthrough), and spawns.

Where most of my engineering effort has gone:

- Custom CLI generators (`new-lineup`, `new-scenario`) that take raw in-game console coordinates
  and append validated entries to the dataset
- A single `npm run validate` pipeline — typecheck, lint, tests, data-integrity scripts, build
- Playwright end-to-end tests and GitHub Actions for CI and Pages deployment
- Graceful fallbacks so content is usable before screenshots exist

---

## Other projects

**[River_Permit_Tracker](https://github.com/DavidPurvis/River_Permit_Tracker)** — Python

Polls recreation.gov for permit availability on the Green River through Gates of Lodore
(Dinosaur National Monument) and sends email or push notifications when new dates open up.
Permits there are scarce and get claimed fast, so the useful part is noticing before a human would.

**[River-Gauge-Web-App](https://github.com/DavidPurvis/River-Gauge-Web-App)** — Python · Flask

Tracks real-time river flow (CFS) for runs near Glenwood Springs, CO. It replaced a physical
whiteboard that had to be updated by hand and often went stale for days — which matters when a
100 CFS swing meaningfully changes features on the river.

**[pulsar-battery-controller](https://github.com/DavidPurvis/pulsar-battery-controller)** — Python

A StreamController plugin surfacing Pulsar X3 Mini mouse battery and DPI on Stream Deck keys and
dials, with a Flatpak-safe host adapter and a shared polling cache.

**[streamcontroller-styled-widgets](https://github.com/DavidPurvis/streamcontroller-styled-widgets)** — Python

Matching Weather, Clock, and Date widgets for StreamController, sharing one high-contrast visual
system across keys and dials.

---

## Tools I work with

Python · TypeScript · Flask · Vite · Playwright · GitHub Actions · Git
