# 40k workspace

My Warhammer 40,000 hobby: an Adeptus Mechanicus army, lists, rules reference and plans. Hermes (via Matrix) and Claude both work here.

## Layout

- `army.md`: **the source of truth.** Current list, collection, plans, paint state. Read it first, and update it whenever the list, collection or plans change.
- `rules/quick-reference.md`: core rules, army rules, detachments and every owned or candidate unit, as summaries with stats and points.
- `rules/cheat-sheet.md`: the game plan and turn-by-turn play aid for the current list.
- `lists/`: list exports from New Recruit or BattleScribe (`.ros`, `.rosz`, `.json`, `.txt`), each with a readable `.md` next to it. Name files `YYYY-MM-DD-<name>.<ext>`.
- `notes/`: free-form ideas, painting plans, matchup notes, battle reports.

## Rules for content (this repo is public)

- **Rules text can quote official wording directly** (datasheets, abilities, stratagems), or summarise it; whichever reads better for play. Don't commit official PDFs.
- **No lore.**
- **Get rules and points from current sources, not memory.** Use Wahapedia 11th-edition pages and the official Faction Pack / Munitorum Field Manual. Points change with every balance update, so stamp the date and source when you update numbers, and tell me to confirm them in New Recruit.
- **Tie suggestions to what I own,** or to a concrete swap with the points it frees.

## Publishing

GitHub Pages serves this repo from `main`: <https://narfman0.github.io/40k/>. Markdown renders automatically. Link between pages with relative `.md` links; Pages rewrites them.

## Git

One branch: `main`. Run `git pull` before starting, since Hermes, Claude and I all edit here. Commit small changes straight to `main` and push every time. No feature branches, no unpushed commits.
