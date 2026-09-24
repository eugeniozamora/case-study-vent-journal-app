# Byrnit — Vent It, Burn It

An anti-cozy journaling app. No streaks, no gratitude prompts, no soft pastel calm. You write what's actually bothering you, and then you burn it — the entry is gone, on purpose.

Solo-built and taken from brand concept through to store-ready release: positioning, UX, mobile build, CI/CD, launch assets.

![feature graphic](./assets/feature-graphic-1024x500.png)

## The idea

Most journaling apps are built around permanence and positivity — keep every entry, build a streak, reflect on growth. That's the right product for some people and the wrong one for anyone who just needs to get something out of their head *right now*, without it becoming a permanent record they'll reread at 2am.

Byrnit's core mechanic is deletion as a feature: write the vent, then burn it. Local-first — the entry never has to leave the device to do its job.

## From concept to store, one deliberate stage at a time

This wasn't "build the app then figure out branding." Each stage shipped as a checkpoint:

1. **Validation** — is "anti-cozy journaling" an actual gap, or just a contrarian idea? Validated against existing cozy-journal competitors before writing a line of UI code.
2. **Brand** — the "vent it, burn it" identity, tone of voice, and visual language, decided before screens were designed so the UX had a personality to be consistent with.
3. **UX** — screen flows built around the one mechanic that matters: write → burn. Everything else stays out of the way of that.
4. **Build** — Flutter app, local-first storage, no account required to use the core loop.
5. **Launch** — store assets, feature graphics, Play Console submission, landing page with its own privacy policy.

## Tech stack

| Layer | Choice | Why |
|---|---|---|
| App | Flutter / Dart | single codebase, iOS + Android |
| Storage | Local-first | the "burn" mechanic requires deletion to actually mean deletion — no server copy to forget about |
| CI/CD | Codemagic | automated build/release pipeline for store submissions |
| Landing | Static site (own domain) | privacy policy, positioning, download links |

## Why this is in the portfolio

Every other project here is client or team work inside an existing system. This one is the opposite proof point: taken solo from "is this idea worth building" to a store-submitted app, including the parts that aren't code — positioning, visual identity, release logistics.

## What's in this repo vs. what's not

This extract includes the brand/UX narrative, screenshots, and store assets. It omits the production `lib/` source, the app-signing keystore, and any unfiltered strategy notes — those stay private.
