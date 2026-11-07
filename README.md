# That 70's Channel — Website Redesign Concept

A one-page, mobile-first pitch concept for [That 70's Channel](https://www.that70schannel.com/) (Boss Radio Group / Live365).

**Live preview:** https://jamesonflex.github.io/that-70s-channel/

## Features
- Three.js (r128) 3D background: disco balls, vinyl records, lava-lamp blobs and sparkles. Reacts to touch, mouse and scroll; tap objects to spin them. 2D canvas fallback if WebGL/three.js is unavailable.
- Animated logo: spinning vinyl, rotating sunburst light beams, disco ball and sparkles. Drag to tilt, tap to boogie. Exports: `assets/logo-animated.gif` and `assets/logo-animated.webp`.
- "On Air" card + day-by-day host cards (Pacific time) from the station's real schedule.
- Ways to Listen cards with 3D tilt.
- Pop-up Live365 player (station `a09646`) with minimize-to-pill, close and "Open full player".
- 70s Arcade: Groove Catcher, Far-Out Flip memory match, Name That Groove trivia. Best scores saved on the device.
- 6-step Request a Song funnel that sends through FormSubmit AJAX to the `REQUEST_TO` address.
- Station shop callout, "More from the family" sister stations, social links and footer.

## Settings to check
In `index.html`, near the top of the main `<script>`:
- `STATION_ID` — Live365 station ID (`a09646`)
- `REQUEST_TO` — where song requests are emailed. FormSubmit sends a one-time activation email to this address on the first request; it must be confirmed before requests are delivered.

## Deploy
Settings → Pages → Branch: `main` / `(root)` → Save.

© That70sChannel™ Boss Media Worldwide: BBR Productions, Inc. This repo is an unofficial redesign concept.
