# Project status — Household Food

Last updated: 2026-11-01 by Jay (Claude Code)

## Current state (2026-11-01, reported by Kovas; this overrides older text below)
- **Cooking now:** one chuck roast half is braising at 300°F. Follow [`cooking/ROAST_FINISH_CARD.md`](cooking/ROAST_FINISH_CARD.md). The other half is in a prepared freezer bag.
- **Groceries:** Costco is done, the King Soopers order is picked up, and there was one extra King Soopers trip. Receipts are in the ChatGPT chat and **not yet in this repo**, so item lists and quantities here are unverified.
- **New rule:** no dairy milk in recipes. Sour cream and pasteurized cheese stay. Existing plans that use milk aren't updated yet.
- **In progress:** a quality audit, new menu, 10-minute cook plan, freezer labels and weekly system. **Don't cook from Cook Day 1 or Cook Day 2 until these are published**, apart from the roast card.

**ChatGPT:** please write out the receipts and updates Kovas gave you, as text he can paste to Jay.

## Older status (2026-10-31)

**Phase:** Groceries partly done. **King Soopers order placed by Kovas (2026-10-31).** Costco trip **not done**, so **Cook Day 1 and Cook Day 2 are postponed** until Costco (the chicken, mushrooms, green beans, broccoli, short ribs and ground beef all come from Costco).

## What to do next (Kovas)
1. **Pick up the King Soopers order.** Put the cold and frozen items away right away. **Beef stir-fry strips:** if the Costco trip and Cook Day are more than **3 days** away, **freeze them now** in their package (label the date).
2. **Costco trip:** use [`COSTCO_LIST.md`](COSTCO_LIST.md) (ChatGPT can read it out). Section A unblocks Cook Day 1.
3. **Cook Day 1** (≤150 min) using [`cooking/COOKING_GUIDE.md`](cooking/COOKING_GUIDE.md) on the same day as, or the day after, the Costco trip. Cook Day 2 can follow the next day.
4. After each step, tell Jay (or ChatGPT, which tells Kovas to tell Jay) what was **actually** bought, made and frozen.

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

- **Day 2 recipes (new, untested):** Braised Bone-In Short Ribs (wine-free: reduced stock + gelatin + vinegar in two stages) and Creamy Ground Beef Noodles (coconut aminos instead of Worcestershire; sour cream and noodles added at serving). Based on ATK and Serious Eats techniques. The 'Philly's Phavorites' original couldn't be found or seen.
- **Audio-friendly cooking guide** with stage timelines: [`cooking/COOKING_GUIDE.md`](cooking/COOKING_GUIDE.md).

## Active
| Task | Owner | Status (PLANNED vs ACTUAL) |
|---|---|---|
| Costco trip | Kovas | **not done**; list expanded for the next trip |
| King Soopers pickup cart | Jay built; Kovas reviews, picks a pickup time, pays | **complete**: 54 items, est. $176.59 before tax, substitutions off. **Not ordered** |
| King Soopers order | Kovas | **placed** (reported by Kovas 2026-10-31; Jay didn't view the order confirmation). Pickup pending |
| Cook Day 1 | Kovas | **postponed**: waiting for the Costco proteins and mushrooms |
| ChatGPT access to the private repo | Kovas (from ChatGPT) | **unverified** |

## Blockers
1. **Chrome: RESOLVED 2026-10-31 ~15:20.** Fixed by restarting Chrome and checking the extension's signed-in account. **King Soopers site outage (~15:45):** the cart shows its lines as "Unavailable". Jay retries.
2. **Prices and coupons unverified:** King Soopers digital coupons and the weekly ad need the signed-in browser session. Costco's coupon book (Oct 19 – Nov 15, 2026) applies automatically at the register.

## Questions ChatGPT should be able to answer from these files
- Next step: "What to do next" above.
- What's in the freezer: [`COOKING_PROGRESS.md`](COOKING_PROGRESS.md). **ACTUAL** columns only; nothing has been made yet.
- Today's list and order status: [`SHOPPING_STATUS.md`](SHOPPING_STATUS.md).
- Batch cost: [`COOKING_PROGRESS.md`](COOKING_PROGRESS.md) cost table (filled from receipts; none yet).
- Backlog: [`BACKLOG.md`](BACKLOG.md).
