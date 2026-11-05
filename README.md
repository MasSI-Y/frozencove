# FrozenCove — Third-Person Action Prototype (Unreal Engine 5.4)

A learning project I built in Unreal Engine 5.4 in summer 2026. I first built it by following a teacher's course, then rebuilt it again on my own to make sure I actually understood each system. It is **unfinished** — this repo documents what works so far and what I learned from building it.

## Current State

**Working:**
- Playable third-person character with basic (normal) attacks
- One AI-controlled enemy
- Player and enemy health bars
- Gameplay HUD in UMG: character portrait, health bar, and a four-slot ability bar

**Not yet implemented:**
- The four abilities are UI only — the skill icons and bar exist, but the skills do not fire in-game yet
- More enemy types, win/lose flow, and menus

## What I Learned

- UE5 project structure and level setup (the FrozenCove arena: snowy ruins environment, 840+ actors, blocking volumes for the playable space)
- UMG widget blueprints: building a HUD and wiring health values into progress bars
- Basics of AI controllers and character setup in Unreal

## Next Steps

- Implement the four abilities for real (input → gameplay effect → cooldown UI)
- Add enemy variety and a simple encounter/win condition

## Tech

- Unreal Engine 5.4, Blueprint
- Character/environment art: Epic Paragon assets & Starter Content (used under their license; not redistributed here)

## Screenshots

_(add 2–3 screenshots — your editor shot of FrozenCove works)_
