# BrokeTheCycle

**Get through the next 10 minutes.**

BrokeTheCycle is a web-based craving support tool that helps people overcome addiction — not by counting streaks, but by getting you through the moment that matters: the craving. Native Android and iOS apps are on the roadmap.

---

## The Problem

Most recovery apps are streak counters with a journal bolted on. They turn recovery into a game where one slip = total failure. Users download in a moment of crisis, log 4 days, relapse, feel ashamed of the broken streak, and delete the app. The streak *is* the problem.

**BrokeTheCycle takes a different approach.** A craving peaks and fades in 10–20 minutes. The entire app is optimized for surviving that window — not tracking the months around it.

## How It Works

### The Craving Button

One big button on the home screen: **"I'm having a craving."**

Tap it and you're dropped straight into a guided protocol. No menu, no choices, no thinking. The app decides for you because thinking is what fails in a craving.

### The 4-Step Protocol (~10 minutes)

1. **Breathe** (2 min) — 4-7-8 breathing with an animated circle and per-second countdown. Breathe in for 4, hold for 7, breathe out for 8. No decisions. Just follow the circle. Calms the nervous system before anything else.
2. **Name it** (~1 min) — Identify the trigger from a set of tags and rate the intensity 1–10. Fast, tap-only. No typing. Captures data even if you bail after this step.
3. **Move** (5 min) — Pick one physical action from a short list (cold water, push-ups, change rooms, go outside, drink water). Then a quiet 5-minute countdown. The screen is deliberately boring — put the phone down.
4. **Reflect** (~2 min) — Rate the craving intensity again. Log what helped. Optional free-text note. Your personal goals are shown as a closing reminder of what you're building.

Each step is time-locked but every step has an **"I'm okay now"** exit button that saves whatever's been captured and returns you home. Partial sessions still produce useful data. Empty exits during Breathe don't clutter the log.

No meditation fluff. No motivational quotes. Just a structured protocol to get you to the other side.

### Craving Log

Every craving is data. The log shows patterns over time — which triggers repeat, what time of day hits hardest, which coping steps actually work for *you*. Completed sessions show the intensity drop (e.g. 8 → 3). Partial sessions are marked so you can see which steps you tend to exit at.

### Day Tracking

Simple daily check-in: smoke-free or smoked. A 30-day dot grid on the home screen shows the pattern at a glance. No streak counter — just honest data.

## Design Principles

- **Zero friction at crisis.** Tap icon → tap button → breathing starts. No login, no account, no email.
- **Privacy by default.** All data stored locally in your browser. No backend, no analytics SDK, no third-party tracking. Your recovery data never leaves your device.
- **No shame, ever.** The app is designed so people come back after a slip instead of disappearing. A relapse doesn't reset anything.
- **Direct, warm, never preachy.** Think: a thoughtful friend who knows recovery. Not a wellness app, not a clinician. No "journey." No "warrior." No "champion."

## Tech

- Single HTML file. Vanilla JS. No framework, no build step.
- localStorage only — works offline after first load.
- Responsive, mobile-first (max-width 480px).
- Light/dark mode via `prefers-color-scheme`.
- Add to iPhone/Android home screen for app-like experience (full-screen, no browser chrome).

## Roadmap

- [x] Craving Button + 4-step protocol (Breathe → Name → Move → Reflect)
- [x] 4-7-8 breathing with animated circle and per-phase countdown
- [x] Craving log with pattern tracking and intensity drop
- [x] Day tracking with 30-day dot grid
- [x] Local-only storage (privacy first)
- [ ] Resilience Score — composite metric that replaces streaks (dips on relapse, never resets)
- [ ] Calming visual redesign
- [ ] PWA support (installable on mobile home screens, offline-first)
- [ ] Push notifications for daily check-in
- [ ] Native Android app
- [ ] Native iOS app
- [ ] Peer connection — anonymous voice calls with someone 6+ months sober
- [ ] AI companion — learns your triggers, proactively pings before high-risk moments
- [ ] Family/sponsor tier with shared resilience signals (user-consented)
- [ ] Treatment center partnerships (B2B)

## Why "BrokeTheCycle"?

Addiction is a loop — trigger, craving, use, shame, repeat. Recovery isn't about willpower. It's about breaking the cycle, one craving at a time. The name is the proof.

## Contributing

This is currently a solo MVP. If you're interested in contributing — especially if you have lived experience with recovery — open an issue and let's talk.

## License

GNU Affero General Public License v3.0 — free to use, modify, and distribute, but all derivative works (including hosted versions) must remain open-source under the same license.

---

*Built because someone at 11pm deserves better than a broken streak counter.*
