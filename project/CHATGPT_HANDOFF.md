# ChatGPT handoff — Household Food project

**Read this file first.** Jay (Claude Code) keeps it current, so Kovas doesn't have to paste anything. Publishing to GitHub is the only sync step; there is no live sync.

- **Public repo:** `kkulbis1/food-picker-dk4axu`, https://github.com/kkulbis1/food-picker-dk4axu (branch `main`). Commit history: https://github.com/kkulbis1/food-picker-dk4axu/commits/main
- **Private repo:** `kkulbis1/kovas-…-food-private` (PRIVATE; full name withheld from public docs, so look for it in the connector's repo list). It holds the raw responses, the full profile and private context. You can read it only through the ChatGPT GitHub connector, and only if Kovas has granted that connector access to this repo. **Access has not been verified.** If you can't open it, say so, and don't guess at its contents.
- **Snapshot:** 2026-10-31 ~16:30 MT. Day 1 plan v2.2 + Day 2 new recipes v1 + cooking guide.

## Raw files (no login)
- https://raw.githubusercontent.com/kkulbis1/food-picker-dk4axu/main/project/STATUS.md
- https://raw.githubusercontent.com/kkulbis1/food-picker-dk4axu/main/project/COSTCO_LIST.md
- https://raw.githubusercontent.com/kkulbis1/food-picker-dk4axu/main/project/PLAYBOOK.md
- https://raw.githubusercontent.com/kkulbis1/food-picker-dk4axu/main/project/SHOPPING_STATUS.md
- https://raw.githubusercontent.com/kkulbis1/food-picker-dk4axu/main/project/COOKING_PROGRESS.md
- https://raw.githubusercontent.com/kkulbis1/food-picker-dk4axu/main/project/DECISIONS.md
- https://raw.githubusercontent.com/kkulbis1/food-picker-dk4axu/main/project/BACKLOG.md
- https://raw.githubusercontent.com/kkulbis1/food-picker-dk4axu/main/project/cooking/COOKING_GUIDE.md  ← **use this for live, step-by-step cooking help**
- https://raw.githubusercontent.com/kkulbis1/food-picker-dk4axu/main/project/cooking/2026-10-31_Cook_Day_1.md
- https://raw.githubusercontent.com/kkulbis1/food-picker-dk4axu/main/project/cooking/2026-11-01_Cook_Day_2_New_Recipes.md
- https://raw.githubusercontent.com/kkulbis1/food-picker-dk4axu/main/project/FILE_INDEX.md

Raw files can be cached for a few minutes after a push. These files override chat history. If they conflict with what Kovas says, ask him.

## Answering common questions
| Question | Where |
|---|---|
| What's on my Costco list? | Read `project/COSTCO_LIST.md`, section by section. Section A is required before cooking |
| How do we run this system? | `project/PLAYBOOK.md` |
| What should I do next? | STATUS → "What to do next" |
| What has Jay completed? | STATUS → "Completed (verified)" |
| What's on today's shopping list? | SHOPPING_STATUS |
| What is blocking the grocery order? | STATUS → Blockers; SHOPPING_STATUS → order status |
| What meals are actually in the freezer? | COOKING_PROGRESS → inventory (ACTUAL). Report only ACTUAL rows; PLANNED isn't made |
| What did each batch cost? | COOKING_PROGRESS → batch cost (from receipts only) |

## Current status
- **Plan:** Today: 16 two-person meals (12 pans B + 4 RAW bags C) within 150 active min. Sunday: Braised Short Ribs ×3 + Creamy Ground Beef Noodles ×3 (D). **Nothing is made yet. The new recipes are untested.**
- **Groceries:** Costco list is ready. The King Soopers cart is **not built**; the Chrome extension isn't connected to Jay's session. A fallback list is in SHOPPING_STATUS. **No order has been placed.**
- **Prices and coupons:** not verified.

## Please review (independent check)
1. Cook Day 1 v2 food safety:
   - chilling assembled casseroles in the fridge before freezing
   - raw-first workflow
   - 165°F checkpoints
   - thawing
2. The sodium estimates table: recompute from the stated assumptions.
3. Shopping completeness against the recipes.
4. Session 2 ideas that meet DECISIONS and lean nutrition-forward. Mark new suggestions 🆕.

## Cooking-guide mode (when Kovas is cooking)
- Read `COOKING_GUIDE.md` **one stage at a time**, in short sentences. Wait for "next." Always read the 🛑 safety line aloud.
- Don't change amounts or temperatures. If Kovas asks for a substitution, check it against DECISIONS (GF, no alcohol, no fish/anchovy, mild) before agreeing.
- Afterward, tell Kovas to report to Jay what was actually made, so COOKING_PROGRESS can be updated.

## Rules for ChatGPT
- Read these files; don't ask Kovas to paste Jay's output.
- Never copy private-repo content into this public repo, and never ask for it to be copied here.
- Don't keep a competing task list. Kovas brings your results back to Jay (or they go into `project/reviews/` if you have write access).
- Make no medical claims. The individual sodium target is the clinician's decision and isn't known yet.
