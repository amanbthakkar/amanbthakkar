# Hi, I'm Aman Thakkar

Engineer @ Meta · Sunnyvale, CA

AGI is already here — what's left is learning to orchestrate it. By day I work on AI products. By night I run a personal superintelligence at home: a Raspberry Pi stack that watches my house, my car, my finances, and my calendar — and acts on them, with a human tap where it matters.

## Agentic systems I built and run in production

- **[muse-mailbox](https://github.com/amanthakkar/muse-mailbox)** — End-to-end encrypted messaging *between Muse instances*. A blind Cloudflare relay that can't read a word (Ed25519 + X25519 + AES-256-GCM), directional credentials, idempotent delivery, threading + acks. Frozen protocol, threat model, and honest field notes from running it live since Sep 2026.
- **[musebook](https://github.com/amanthakkar/musebook)** — Private boards for your family's Muses. An open protocol + Muse skill + Cloudflare Workers reference server: per-board identities, Ed25519-signed posts, and human approval before any Muse acts externally.
- **Cortex — my homelab agent stack** *(private monorepo)* — A Telegram agent on a Raspberry Pi backed by a Postgres "Cortex" service: Home Assistant automations, TeslaMate + Tesla Fleet Telemetry for my Model Y ("Scarlet"), a fitness/nutrition backend, and self-hosted media, photos, documents, and finance. The public protocols above are the pieces of it I could open-source cleanly.
- **[openledger](https://github.com/amanthakkar/openledger)** — Privacy-first, self-hosted personal finance: Next.js + FastAPI + Postgres + Plaid, encrypted provider tokens, localhost by default. Your bank data stays home.

## Open-source contributions

First community skills proposed to Meta's **[muse-gadget-sdk](https://github.com/facebookincubator/muse-gadget-sdk)** catalog:

- [PR #222 — Tesla + Nest skills](https://github.com/facebookincubator/muse-gadget-sdk/pull/222): Tesla via self-hosted Fleet API / TeslaMate / Fleet Telemetry analytics, and Google Nest thermostats via the Smart Device Management bridge.
- [PR #224 — Bambu Lab skill](https://github.com/facebookincubator/muse-gadget-sdk/pull/224): printer status (cloud/LAN) and Developer-Mode dispatch for Bambu Lab printers.

## Research & earlier work

- **[crypto_finance](https://github.com/amanthakkar/crypto_finance)** — Quantitative crypto research as runnable notebooks: efficient portfolios, logarithmic regression "rainbows", stock-to-flow (and its limits), and a power-law oscillator — each with a long-form article. The oscillator runs live, updated daily, at [amanthakkar.com](https://www.amanthakkar.com/power-law-oscillator-indicator/?source=github).
- **[microservices-docker-k8s-mongodb](https://github.com/amanthakkar/microservices-docker-k8s-mongodb)** — Event-driven microservices from scratch (event bus, CQRS-style read model, K8s manifests) — built to learn the architecture by building it.

## How I work

I build with agents, in the open where I can: protocols before code, threat models in the README, field notes when production teaches me something the design didn't. If a project here is archived, it's a course or a clone I learned from — kept for honesty, not for show.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/amanbthakkar) · [X](https://twitter.com/TheTweetsOfAman) · [amanthakkar.com](https://amanthakkar.com)

Chelsea FC, 3D printing, and an unreasonable amount of Tesla drive data.
