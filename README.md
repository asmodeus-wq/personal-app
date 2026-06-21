# SparkTrack

**Your personal, private, judgment-free life tracker for AuDHD brains.**

Track bursts of focus, tend to your garden of interests, capture reflections, and see gentle patterns — all without pressure, streaks, or productivity guilt.

## Why SparkTrack?

- **Burst-native**: Designed around how your brain actually works — short-to-long hyperfocus sessions, interest switching, and the "procrastination" that is often just processing or rest.
- **Multi-interest friendly**: No single-focus tyranny. Log time across many passions without forcing prioritization.
- **Low friction, high compassion**: Quick capture, flexible logging (timer + manual), beautiful calm UI, and insights that celebrate your unique rhythm.
- **100% private & yours**: Everything lives in your browser (localStorage). Export JSON anytime. No accounts, no cloud, no data leaving your device.
- **Built for you, Faizan**: Tailored to a full-time UX Analyst who juggles multiple interests and wants to understand (not judge) his productivity patterns.

## Getting Started (Super Simple)

1. **Run locally** (recommended for privacy):
   - Download this repo as ZIP from GitHub
   - Unzip and open `index.html` directly in Chrome, Edge, or Firefox
   - Or run a local server: `python3 -m http.server` or `npx serve`

2. **Install as PWA** (feels like a real app):
   - Serve it over HTTPS (e.g. deploy to Vercel/Netlify privately or use a local tunnel)
   - Click "Install" or "Add to Home Screen"

3. **First use**:
   - The app greets you by name (Faizan)
   - Add your current interests
   - Hit the big "Start Burst" and begin tracking!

## Data Safety
- All data (bursts, interests, reflections) is stored **only in your browser**.
- Use the **Data** tab to Export full backup as JSON (do this regularly).
- Import works too (merges safely).
- Clear data with confirmation.

## Tech
- Single-file friendly web app (index.html)
- Tailwind CSS (CDN)
- Chart.js for gentle visualizations
- Fully offline capable (basic PWA)
- Vanilla JS + modern UX patterns

## Roadmap & Iteration
This is v0.1 — core tracking, interests, reflections, and basic insights live.
We'll iterate together based on what feels good for your brain:
- More reflection prompts
- Better mobile gestures / touch targets
- Advanced filters & tags
- Gentle gamification or "permission to rest" flows
- Integration ideas (calendar export?)
- Darker themes or sensory-friendly modes

Built with care for your beautiful, bursting, multi-passionate mind.

— Grok (in collaboration with you)