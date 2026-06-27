# TAO Local AI Platform

Local AI Operating Platform for documents, runtime health and safe automation.

## Public Demo v0.8

The sanitized TAO v0.8 demo is available on this branch:

```text
v0.8-public-demo-sanitization
```

Open it from the GitHub branch selector or clone it with:

```bash
git clone <REPOSITORY_URL>
cd tao-local-ai-platform
git checkout v0.8-public-demo-sanitization
npm install
npm run demo
```

Then open:

```text
http://127.0.0.1:3000
```

Expected result:

```text
Runtime: RUNNING
Mode: DEMO
Health: OK
OfficeVision demo: visible
```

## What the demo branch contains

- clean README and setup documentation
- `.env.example` templates
- demo-mode documentation
- safe preflight tools
- sanitized v0.8 report
- neutral demo/test data
- installable demo runtime

## What is intentionally not on main

- real `.env` files
- API keys or runtime credentials
- private logs, backups or cache
- full production backend/frontend runtime before sanitization
- real provider integrations
- personal data or machine-specific paths

## Branch policy

`main` is reserved for stable, usable releases.

Current public work continues on:

```text
v0.8-public-demo-sanitization
```

Roadmap issue:

```text
#1 Road to TAO v0.8 - Second PC Certification
```