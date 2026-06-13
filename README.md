# AppADay #037 — Last Call

A bar/taproom-themed Pac-Man clone, part of the AppADay project (one app shipped every day).

## What it does

You play a bartender making the rounds through a maze of bar tables, eating barley kernels (dots) for points. Four “barfly” ghosts roam the floor with classic arcade-style chase, ambush, patrol, and flee-when-close personalities — collision costs you a life. Eating a hop cone (power pellet) turns the barflies woozy, letting you eat them for 200 points each (with a floating “+200” popup); once eaten, a barfly is kicked out for the rest of the level — though the bar is never empty, since one will always sneak back in through the side corridor if all four are gone. A pretzel appears periodically for a 100-point bonus (”+100” popup). Clear every kernel to advance to the next level.

Levels cycle through four themed venues, each with its own maze layout and color palette: The Tap Room, The Biergarten, The Nightclub, and The Venue. Ghost speed increases with each level. Score and lives carry across levels, and every 10,000 points earns an extra life (“Extra Beer!”). Three lives to start; lose them all and it’s last call.

## Controls

On a touchscreen, swipe anywhere on screen to set direction. On a keyboard (non-touch devices), use arrow keys or WASD. The board stretches edge-to-edge on any screen size.

## Debug

Press number keys 1–9 to jump straight to that level, or `[` / `]` to step down/up one level — useful for testing each venue and ghost-speed tier.

## Tech

Single-file HTML/CSS/JS, HTML5 Canvas rendering, no external libraries or build step. High score persists via localStorage (wrapped in try/catch for sandbox safety).

## Part of AppADay

Daily app-building challenge — one complete, polished web app published every day. Full portfolio: <https://augustineiacopelli.github.io/appaday/>
