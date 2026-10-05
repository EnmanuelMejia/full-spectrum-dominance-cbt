# Full Spectrum Dominance — Enterprise-Grade CBT

An interactive, adaptive computer-based training course built to prepare a cybersecurity candidate to dominate technical interviews — "full spectrum dominance" across the domains employers actually test.

**Live:** https://interstitiumlabs.dev/bootcamps/full-spectrum-dominance/
Also deployed on https://learn.interstitiumlabs.dev and https://enmanueldmejia.com

## What's inside

| Pillar | Content |
|---|---|
| ThreatLocker interview prep | Zero Trust endpoint security concepts: allowlisting/denylisting, ringfencing, elevation control, application control — framed as interview-ready talking points and scenario drills |
| Think Like an Attacker — security graphs | Graph-theory defense concepts drawn from Dr. Chase Cunningham's *Think Like an Attacker*: attack graphs, kill-chain mapping, link analysis, insider-threat detection, and graph-driven Zero Trust enforcement (microsegmentation, relationship-based access control) |
| AI-powered cybersecurity | ML-assisted threat detection, anomaly detection on security graphs, predictive analytics, and defensive automation |
| Adaptive drills | 44 scored scenarios across the domains, with an adaptive queue that targets your weakest areas first |
| Lessons & labs | 9 structured lessons and 9 guided hands-on labs |
| Simulated terminal / console | Browser-based terminal, console, and mission simulations — no installs, nothing leaves your device |

## How it works

- **Interactive** — scenarios are hands-on scored decisions, not reading material.
- **Adaptive** — the drill queue targets weakest domains first; per-domain mastery is tracked locally in your browser (localStorage, nothing leaves your device).
- **Independent** — interview-prep material by Interstitium Labs. Not affiliated with, endorsed by, or sponsored by ThreatLocker or any vendor mentioned. Confers no certificate. All scenarios are original practice content; no exam or vendor-training content is reproduced.

## Run it

Open `index.html` in any browser — self-contained, zero dependencies. `chat/index.html` is the conversational practice companion.

Source content lives in `source/` (`full-spectrum-dominance.json` plus the fragment files it was assembled from). `content.json` is the deployed payload; `engine/` is the shared bootcamp runtime (lessons, labs, terminal, console, missions, chat, simulations).

Built by [Interstitium Labs](https://interstitiumlabs.dev) — Enmanuel D. Mejia, Founder.
