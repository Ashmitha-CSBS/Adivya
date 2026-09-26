# 🌱 Adivya — Scholarship Journey Companion

**From opportunity to achievement.**

Adivya is a privacy-first web app that helps students — especially from underprivileged and tribal communities — go beyond just *finding* scholarships to actually *winning and keeping* them. Instead of acting like a passive database of schemes, Adivya works like a companion that guides students through the whole journey: discovering opportunities, checking eligibility, preparing documents, avoiding last-minute mistakes, and tracking renewal year after year.

## Why Adivya

Most scholarship portals dump long eligibility PDFs and rigid deadlines on students who are already navigating complex paperwork alone. Adivya flips that — every screen answers one question: **what should I do next?**

## Features

| Feature | What it does |
|---|---|
| 🎯 Opportunity Radar | Add scholarships you've found; Adivya scores how well each matches your profile and explains why |
| 🧠 Eligibility & What-If Simulator | Plain-language rule breakdown, plus a sandbox to test different income/tier scenarios without touching your real profile |
| 🧾 Document Vault | Mark documents ready once, reuse them across every application |
| 🚨 Rescue Mode | Automatic focused checklist when a deadline is within 48 hours |
| 📋 Application Tracker | One place for every application's status and deadline |
| 🌳 My Journey | A Seed → Sapling → Mature Tree progress visual, plus a shareable achievement card with no sensitive data |

## Privacy by design

Nothing is pre-filled. Every student creates their own account, and all profile, document, and application data lives only in their own browser's local storage — nothing is seeded, shared, or visible to anyone else.

## Tech stack

A single self-contained HTML file — no backend, no build step, no dependencies. Runs anywhere: locally, GitHub Pages, Netlify, or any static host.

## Getting started

**Run locally:**
```bash
git clone https://github.com/Ashmitha-CSBS/Adivya.git
cd Adivya
python -m http.server 8000
# open http://localhost:8000
```

**Or deploy:**
Just push `index.html` to the repo root — Netlify, Vercel, or GitHub Pages will serve it with zero configuration.

## Roadmap

- [ ] Real backend + database for cross-device sync
- [ ] Multilingual voice assistant
- [ ] Offline-first mode for low-connectivity areas
- [ ] AI-powered document mismatch detection

## License

MIT
