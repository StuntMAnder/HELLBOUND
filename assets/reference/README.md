# HELLBOUND Art Integration

## Approved reference sources
- `animation-reference.webp`: the first supplied reference sheet. Use its masked Phantom design (helmet/face fully covered) as the canonical Phantom reference.
- `character-reference.webp`: the second supplied character sheet. Use Hank and Reaper references from this sheet; do **not** use its unmasked Phantom face.

## Animation categories visible in the supplied sheet
Stand, walk, crouch, guard, dash, jump, attack, grab, hit, and knockdown, plus character-specific attack/effect studies.

## Integration notes
The current browser build still uses procedural stand-ins in the match scene. The reference images are design/animation guides, not yet clean transparent frame atlases. Before using them as in-game sprites, each pose must be separated into its own transparent frame and arranged into a measured atlas. Avoid cropping the labels, neighboring poses, or panel backgrounds into the character frames.

## Facing direction
The game uses opponent-relative horizontal facing. The same frame is mirrored horizontally when a fighter turns; attack direction and effects should follow that facing value.
