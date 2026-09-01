# One Bullet Biscuit — Playtest Report

**Developer:** Moderategrade

**Platform:** itch.io (browser build)

**Genre:** Wave-based zombie survival

**Tester:** Loïc Alexandre (Wattmole)

## Summary
Full playthrough covering multiple rounds and waves, the upgrade shop, and the browser build specifically. My most detailed report of the set, where the developer described it as directly motivating a rebuild of the game.

## Issues Found

| # | Severity | Area | Description |
|---|---|---|---|
| 1 | High | Blocking (browser) | After losing all lives, the mouse cursor is neither shown nor recognized on the Game Over screen, the player cannot restart or quit. |
| 2 | High | Gameplay | Zombies can spawn directly on top of the player near screen borders, causing an unavoidable instant death. |
| 3 | Medium | Collision | Zombie corpses retain a hitbox for a short time after death, repeatedly blocking the player's path and causing avoidable deaths. |
| 4 | Medium | Collision | The two map entry points on the north border form a small pocket where the player can get stuck, only able to move south to free themselves. |
| 5 | Medium | Economy | Exactly 20 cookies cannot purchase a 20-cookie upgrade, despite that being the listed cost. |
| 6 | Low | Flow | Choosing "Next Wave" does not refill ammo even though there is already a pause for the choice between "Next Wave" and "End Round." |
| 7 | Low | Polish | The player character keeps moving during the death animation instead of going idle, undercutting the read of the death. |
| 8 | Low | Unclear | The hatchet-throwing zombie plays its throw animation on contact but nothing happens, unclear if this is intentional (melee-only in range) or a bug. |

## UX / Design Feedback
- The distinction between "Next Wave" (harder, no upgrades) and "End Round" (go to upgrade menu, next round much harder) was not clear and took me about 20 minutes to understand, this confusion, for me, is as the root of most other difficulty complaints.
- No way to retry the specific wave/round just lost. Losing mid-round forces a jump straight into a harder round with fewer resources.
- Difficulty spikes sharply between rounds; without the health upgrade the player is one-shot by everything. Suggested a "grace" mechanic (one hit down to 1 HP instead of instant death) or a recommendation prompt in the upgrade menu.
- No sound or visual feedback when the player takes damage.
- Upgrade costs are not visible outside the upgrade menu, making planning purchases harder for new players.
- Damage-increasing upgrade felt to have no early-game purpose against the giant zombie; bullet-size upgrade effect was imperceptible after one purchase.
- Suggested adding a movement option (dash/roll) or a "parry" option for the hatchet, and throwing it back" mechanic with a cooldown on it.
- Requested a fullscreen option for the browser build, the cursor frequently left the game area and clicked page elements instead.

## Positive Notes
- Sprite work, smooth animations, and the bullet-trajectory guide line were all praised.
- Zombies facing south after a round is lost was noted as a nice touch.

## Developer Response
The developer expressed strong appreciation for the depth of the report and stated it directly motivated them to rebuild and update the game.
