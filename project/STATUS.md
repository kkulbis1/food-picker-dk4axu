# Project status — Household Food

Last updated: 2026-10-31 ~15:00 MT by Jay (Claude Code)

**Phase:** Cook Day 1. The plan has been audited, corrected and independently checked (v2.1). **Today: 12 two-person meals + the enchilada filling (≤120 active min); roll the enchiladas Sun/Mon.** Next: shopping (Costco in person → King Soopers curbside → home), then cooking.

## What to do next (Kovas)
1. **Reconnect the Chrome extension** so Jay can build the King Soopers cart (see Blocker 1). If there's no time, shop from the fallback list in [`SHOPPING_STATUS.md`](SHOPPING_STATUS.md).
2. **Costco run** using the 5-item list in [`SHOPPING_STATUS.md`](SHOPPING_STATUS.md). Report anything that was missing.
3. **Cook** using [`cooking/2026-10-31_Cook_Day_1.md`](cooking/2026-10-31_Cook_Day_1.md) v2.1. Tell Jay what was actually made and frozen.

## Completed (verified)
- Meal questionnaire published at https://kkulbis1.github.io/food-picker-dk4axu/. Preferences collected; profile built (private).
- **Cook Day 1 plan v2.1 (audited; an independent checker found 6 must-fix items, all fixed):**
  - Sodium cut: the beef bag goes from ~2,850 to ~760 mg/serving; all broth unsalted; less added salt.
  - Chicken split between the pressure cooker and the oven because cooker capacity is unconfirmed.
  - Realistic mushroom cook time.
  - Fridge-chill before freezing.
  - Raw-first workflow.
  - Thermometer checkpoints.
  - Labels for the four food states.
  - Beef cooked to 145°F + 3-min rest; a 2-hour clock rule; 4 pans go straight to the freezer.
  - Enchilada sodium corrected to ~720 mg/serving without cheese.
  - Enchilada rolling moved to Sun/Mon to keep today within 120 active min.
- **Private repository created and verified PRIVATE** (`kkulbis1/kovas-…-food-private`; owner is the only collaborator). Holds the original responses (checksum verified on GitHub), private profiles and health context.

## Active
| Task | Owner | Status (PLANNED vs ACTUAL) |
|---|---|---|
| Costco trip | Kovas | planned; not reported |
| King Soopers pickup cart | Jay builds; Kovas reviews, books pickup, pays | **blocked**: Chrome extension not connected to this Jay session |
| King Soopers order | Kovas | not placed |
| Cook Day 1 | Kovas | planned; not started |
| ChatGPT access to the private repo | Kovas (from ChatGPT) | **unverified** |

## Blockers
1. **Chrome:** the Claude extension in Chrome is paired with the Claude desktop app and an older Claude Code terminal session, not with the current Jay session. Fix: in Claude Code, type `/chrome` and choose reconnect. If it asks, click the Claude extension icon in Chrome and sign in to claude.ai with the same account as Claude Code.
2. **Prices and coupons unverified:** King Soopers digital coupons and the weekly ad need the signed-in browser session. Costco's coupon book (Oct 19 – Nov 15, 2026) applies automatically at the register.

## Questions ChatGPT should be able to answer from these files
- Next step: "What to do next" above.
- What's in the freezer: [`COOKING_PROGRESS.md`](COOKING_PROGRESS.md). **ACTUAL** columns only; nothing has been made yet.
- Today's list and order status: [`SHOPPING_STATUS.md`](SHOPPING_STATUS.md).
- Batch cost: [`COOKING_PROGRESS.md`](COOKING_PROGRESS.md) cost table (filled from receipts; none yet).
- Backlog: [`BACKLOG.md`](BACKLOG.md).
