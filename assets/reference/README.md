# HELLBOUND Art Integration

## Uploaded reference sources
- `b0313f06-a6ba-4e09-9a32-348426af1e92.png`: first uploaded sheet. It contains Reaper and Phantom character studies plus labeled pose/effect rows. Preserve the covered Phantom helmet design as the canonical reference.
- `b570b74c-a395-43eb-87c3-7aa79a01e744.png`: second uploaded sheet. Use its Hank and Reaper designs as references. Do not use its unmasked Phantom face.

## Animation categories shown
Stand, walk, crouch, guard, dash, jump, attack, grab, hit, and knockdown, with character-specific attack and effect studies.

## Current implementation — Build 0.5
The browser game now has state-driven procedural animation presentation for idle, walk, crouch, guard, jump, attack, and hit states. Crouch controls are enabled: P1 uses S and P2 uses Down Arrow. Existing opponent-relative facing, attacks, health, meter, and match flow remain in place.

The uploaded sheets are visual reference boards, not clean transparent sprite atlases. Their poses sit on detailed panel backgrounds and include labels and neighboring artwork. They have **not** been cut into production sprite frames or integrated as sprite atlases yet; the current match fighters are still rendered procedurally. The next art-production step is to isolate individual poses, clean their backgrounds, and build measured per-character atlases before replacing the procedural drawings.

## Facing direction
Fighters face their opponents. Character frames and attack effects should mirror consistently with the fighter's facing direction.
