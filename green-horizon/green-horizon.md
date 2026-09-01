# Green Horizon — Playtest Report (2 Builds)

**Developer:** likeaninjamedia

**Platform:** itch.io (browser build, then downloadable beta)

**Genre:** Farming sim

**Tester:** Loïc Alexandre (Wattmole)

## Summary
Tested across two separate builds, the first public playtest, then a downloadable beta after the developer addressed the initial report. Feedback is organized by category to track how the game evolved between builds, demonstrating iterative/longitudinal testing.

## Build 1 — Issues Found

| # | Severity | Area | Description |
|---|---|---|---|
| 1 | Medium | UX/Blocking | After choosing "Move Object" or "Pick up Object," an unlabeled dark rectangle appears bottom-right and blocks interaction with all buildings and the pond except the phone, with no explanation of what it does or how to dismiss it. |
| 2 | Medium | Interaction | The "Rotate (R)" option in the object-move menu does not rotate the item, clicking it drops the object at the cursor position instead. |
| 3 | Medium | State bleed | While in "move object" mode, the player can still open buildings, plant seeds, or move other objects by clicking them directly, instead of being confined to the move action. |
| 4 | Medium | Interaction | Repositioned objects render offset from their actual placement position (below and to the right), making placement feel imprecise. |
| 5 | Low | Visual | Farm-naming text prompt overlaps the "...ll your farm" portion of the underlying text. |
| 6 | Low | UI consistency | Inventory tabs ("Seeds," "Buds," "Plots," "Equipment") are inconsistently sized/aligned. |
| 7 | Low | UX | No notification when a plant finishes growing; the ready-to-harvest sprite state is not distinct enough. |
| 8 | Low | UX | Orders menu doesn't show how many of the requested item the player currently holds, requiring manual inventory checks. |
| 9 | Low | Unclear feature | The well appears interactive but has no function. |
| 10 | Low | UX | Mail menu never populates during the playtest with no "coming soon" placeholder, unlike other unfinished features. |
| 11 | Low | Categorization | The Dry Rack (needed to produce "High Grade" items) is filed under "Equipment" and easy to miss as a core mechanic rather than decoration. |
| 12 | Low | Visual | Placed-item preview sprite sometimes renders under the pond/fence models inconsistently. |
| 13 | Balance | Progression | XP per order (10) felt very low against the 200 XP needed to level up. |

## Build 2 (Beta) — Issues Found

| # | Severity | Area | Description |
|---|---|---|---|
| 1 | Medium | Onboarding | The workbench (required for core progression) is easy to miss in the upper-right corner with no early guidance pointing to it. |
| 2 | Medium | Mission flow | Mission text sequencing is confusing: the objective to "sell 5 bagged seeds" is shown before the player can act on it, since a specific first order must be completed first. |
| 3 | Medium | Regression | Delivery car animation stopped triggering after roughly the 5th delivery, though the delivery itself still completed. |
| 4 | Low | UX | The planting cursor icon persists after the last seed is planted, only clearing once all seeds are used. |
| 5 | Low | Visual | Main-mission reward text overflows past the edge of the in-game phone screen. |
| 6 | Low | Interaction | Shears mini-game hitbox is tied to the mouse cursor rather than the shears sprite, causing inconsistent detection under rapid clicking. |
| 7 | Low | Unclear | No "message from Uncle" mail appears after the second main mission, despite being referenced by the mission text. |
| 8 | Low | Visual | Workbench output text overlaps the "empty bags" line instead of sitting on its own line. |
| 9 | Low | Clarity | Normal and "High Grade" seed sprites are visually identical, requiring a text check to tell them apart. |
| 10 | QoL | Equipment | Fertilizer and watering can un-equip after a single use, requiring re-selection from the inventory for each additional plant. |

## Positive Notes
- Most Build 1 text/overlap issues were fixed by Build 2.
- New planting animation (vs. instant sprite swap) well received.
- Harvest-ready popup added since Build 1.
- Shears mini-game concept liked despite the hitbox issue.
- Border tree sprites improved visually.
- Money pacing felt more generous in Build 2; XP pacing still felt slow for early unlocks.

## Developer Response
The developer called this the game's first public playtest and worked through the reported issues over subsequent updates, several of which were confirmed fixed in the beta build. They also invited me back for further beta feedback rounds.
