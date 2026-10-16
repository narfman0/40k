# 40k workspace

My Warhammer 40,000 hobby: my armies, their lists, rules references and plans. Hermes (via Matrix) and Claude both work here.

## Layout

All armies are equal; none is the default. Each army `<army>` (e.g. `mechanicus`, `necrons`, `custodes`) has:

- `lists/<army>.md`: **the army page, its source of truth.** Current list summary, collection status, plans, paint. It links to its rules page and its latest export, and back to the other armies. Update it whenever that army's list, collection or plans change.
- `lists/YYYY-MM-DD-<army>.<ext>` + `.md`: dated New Recruit/BattleScribe exports with a readable version. The `.md` links back to the army page.
- `rules/<army>.md`: the army's rules reference: army rule, detachment(s), units in the list, candidates. Optional extra play aids are `rules/<army>-<aid>.md` (e.g. `mechanicus-cheat-sheet.md`).

Shared:

- `rules/core.md`: core rules, keywords and core stratagems for every army. Don't duplicate these in army pages; link to them.
- `paints.md`: every paint I own, shared by all armies. Recipes on army pages should use only these, or say what to buy. Update it when I mention new paints.
- `lists/README.md`: index of armies and exports. `README.md`: site home.
- `notes/`: free-form ideas, matchup notes, battle reports. Link the relevant army pages.

**Adding an army:** add its export, army page and rules page, then add it to the nav line at the top of every army page, `lists/README.md` and `README.md`.

## Rules for content (this repo is public)

- **Rules text can quote official wording directly** (datasheets, abilities, stratagems), or summarise it; whichever reads better for play. Don't commit official PDFs.
- **No lore.**
- **Get rules and points from current sources, not memory.** Use Wahapedia 11th-edition pages and the official Faction Pack / Munitorum Field Manual. Points change with every balance update, so stamp the date and source when you update numbers, and tell me to confirm them in New Recruit.
- **Tie suggestions to what I own,** or to a concrete swap with the points it frees.

## Publishing

GitHub Pages serves this repo from `main`: <https://narfman0.github.io/40k/>. Markdown renders automatically. Link between pages with relative `.md` links; Pages rewrites them.

## Git

One branch: `main`. Run `git pull` before starting, since Hermes, Claude and I all edit here. Commit small changes straight to `main` and push every time. No feature branches, no unpushed commits.
