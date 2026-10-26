# GroupBuffToggle — development history

**Author:** Babuni.dev

## Retrospective source study — 2026-10-26

A small Vanilla addon that independently toggles visible party and target buffs beside their unit frames. Its repository provides concrete implementation evidence: GroupBuffToggle.lua creates Blizzard-style checkboxes and adjacent buff displays, showing up to sixteen auras per unit; settings persist in its saved variables. Upgrade-SavedData.ps1 handles renamed addon data. Both displays start disabled, preserving the player's existing UI until toggled; party and target controls remain separate.

These details reveal an approach, not a complete chronology. Original ideas remain credited to Babuni.dev. AI contributed organizing this documentation and did not alter source behavior. Outstanding testing: Test buff tooltip alignment, group changes, aura counts, save/reload and data migration in a 1.12 environment.
