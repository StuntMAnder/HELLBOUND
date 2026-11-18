# HELLBOUND

A browser-based 2D arcade fighter prototype.

## Run it
Open `index.html` in a modern desktop browser. No build tools or dependencies are required.

## Controls
- Player 1: A/D move, W jump, F light, G heavy, H special, T guard.
- Player 2: Left/Right move, Up jump, J light, K heavy, L special, I guard.
- Enter: advance / confirm / rematch.
- Escape: return to fighter select.
- Reset button: return to fighter select.

## Current prototype
- 384 × 224 internal canvas resolution.
- Title screen, two-player fighter select, local match, health bars, timer, attacks, hit reactions, and rematch flow.
- Three distinct temporary procedural character studies: Hank, Reaper, and Phantom.

## Art pipeline
The procedural character drawings are temporary development art, not final approved sprites. Replace them with the approved original sprite sheets when those assets are ready. Keep the internal game resolution and character silhouettes readable at arcade scale.

## Next milestones
1. Replace temporary drawings with approved sprite sheets and animation states.
2. Add proper frame data, hitboxes, hurtboxes, hit-stop, block stun, and combo tracking.
3. Build distinct move lists, specials, supers, round flow, and arcade opponent logic.
4. Add stages, sound, effects, menus, and accessibility options.
