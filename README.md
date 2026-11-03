# Titans League — Animated Manager Prototype

A browser-playable top-down pixel-art expedition prototype built from the original Titans League data.

## Run it
Enable GitHub Pages for this repository (Settings → Pages → Deploy from a branch → main → /root), then open the published URL. The game fetches JSON files, so opening `index.html` directly as a local file may be blocked by browser security; use GitHub Pages or a local web server.

## What this prototype does
- Loads the original player personas, team traits, and environment/room definitions.
- Lets you select two of the 24 teams and a room.
- Uses the original rating-to-stat conversion and room-demand / chance calculation from the legacy game.
- Resolves each squad's attempt before playback, then animates the recorded result.
- Provides play, pause, step, and playback-speed controls.

## Scope
This is the first visual slice, not yet the full season manager. Equipment modifiers, the complete five-room weekly scoring flow, roster management, and campaign progression are future integration work. The visual layer must never independently determine simulation outcomes.

Original rules/data source: https://github.com/brovado/titans-league
