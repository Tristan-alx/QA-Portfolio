# Cairn — Playtest Report

**Developer:** rubic
**Platform:** itch.io
**Genre:** Puzzle platformer
**Tester:** Loïc Alexandre (Wattmole)

## Summary
Short playtest of a block-pushing puzzle platformer. One clear terminal-state issue identified: the game gives no clear signal that it has ended after reaching the top.

## Issues Found

| # | Severity | Area | Description |
|---|---|---|---|
| 1 | Medium | Missing feedback | After reaching the top and the player character disappears, there is no win screen, fade-to-black, or sound cue. It's unclear whether the game has actually ended or whether further interaction (e.g. with the block on the middle pillar) is expected. |

## Positive Notes
- Player-driven block-moving mechanic and the "last player who moved this block" attribution were highlighted as clever.
- Pixel art, music, and the simplicity of each block's properties were well received.

## Notes
Tester explicitly flagged this as the kind of ambiguous end-state that benefits from an explicit resolution screen or audio cue, regardless of which design direction (screen transition vs. continued climb) the developer intends.
