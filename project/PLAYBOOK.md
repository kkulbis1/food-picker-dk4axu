# Playbook — how this household food system runs

For Kovas, Jay (Claude Code) and ChatGPT. Rules live in [`DECISIONS.md`](DECISIONS.md); current state lives in [`STATUS.md`](STATUS.md).

## Roles
- **Jay (Claude Code):** maintains the plans, recipes, lists and both repos, and builds the King Soopers cart. **Never checks out or pays.**
- **ChatGPT:** reads these files, answers questions, reads the cooking guide aloud stage by stage, gives independent review. Doesn't keep its own task list.
- **Kovas:** approves, shops at Costco, checks out at King Soopers, cooks, and reports what **actually** happened.
- **Sync:** GitHub is the only sync. Jay commits and pushes after every milestone. There is no live sync.
- **Receipts and cooking updates must reach the repo.** Anything Kovas gives ChatGPT, such as receipts, purchases or cook state, isn't visible to Jay until it's in the repo. ChatGPT writes it out as text for Kovas to paste to Jay. Jay also checks the ChatGPT chat directly when Chrome is logged in.

## The weekly loop
1. **Plan:** pick dishes from the household's explicit ratings plus the backlog. Aim for about 50% comfort and 50% nutrition. Keep ≤150 min hands-on per session.
2. **Lists:** Costco in person ([`COSTCO_LIST.md`](COSTCO_LIST.md)) → King Soopers curbside (Jay builds the cart).
3. **Cook:** follow [`cooking/COOKING_GUIDE.md`](cooking/COOKING_GUIDE.md). Label every item with its **food state** (ready to reheat · assembled, not baked · RAW bag · fridge ready-to-eat).
4. **Record:** fill in the ACTUAL columns in [`COOKING_PROGRESS.md`](COOKING_PROGRESS.md) (fridge/freezer inventory, receipt costs).
5. **Fridge prep (Sun/Mon):** 3–4 days of ready-to-eat meals; freeze the rest.

## King Soopers cart (lessons from 2026-10-31)
- **Chrome connection:** if Jay sees no browser, quit and reopen Chrome, then open the Claude extension in Kovas's main Chrome profile ("Profile 1") and confirm it's signed in to the same claude.ai account as Claude Code.
- **Kovas signs in to King Soopers himself.** Jay never enters sign-in details.
- Store: **Ridge Village, 5301 W 38th Ave**.
- **Go slowly.** Rapid automated browsing triggered "Cart Didn't Load" errors. Pause about 30 s when they appear.
- **Check every label** in the listing: gluten-free / "free from cereals"; no "may contain wheat"; no alcohol (tamari and soy sauce list alcohol, so use **coconut aminos**); no anchovy (Worcestershire, some dressings); no wine (many Dijons); pasteurized dairy.
- **Substitutions OFF** before handing off. Clip only coupons that match cart items.
- Kovas reviews, picks the pickup time and pays.

## Privacy
- **Public repo** (`kkulbis1/food-picker-dk4axu`): sanitized operating docs only. `tools/publish_public.py` blocks private terms before every push.
- **Private repo** (`kkulbis1/kovas-…-food-private`, owner-only): the original survey responses (never edited), full profiles, health context. Jay keeps it updated.

## Food-safety constants
Poultry 165°F · ground beef 160°F · whole-cut beef 145°F + 3-min rest · reheat everything to 165°F · fridge or freezer within 2 h · thaw in the fridge · cooked leftovers 3–4 days in the fridge · pasteurized dairy and juice.
