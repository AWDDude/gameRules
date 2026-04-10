# AGENTS.md

## Repository Purpose

Documentation-only repository containing complete rule sets for card games. No source code, build system, or tests — just Markdown files.

## Structure

```
README.md          # Index of all games with links
rules/
  euchre.md        # One file per game
  rummy500.md
```

- Each game gets a single Markdown file in `rules/`.
- `README.md` maintains a bullet list linking to every game file.

## Conventions

### Adding a New Game

1. Create `rules/<gamename>.md` (lowercase, no spaces — use the most common short name).
2. Add a link to `README.md` under the `## Games` section, maintaining alphabetical order.

### Rule File Structure

Follow the established pattern visible in existing files. Sections generally appear in this order:

1. **Overview** — one-paragraph summary including player count and deck type
2. **Players / Equipment** — player range, deck composition, any extras (scorekeeping, etc.)
3. **Card Values** — point values or rank hierarchy
4. **Objective** — win condition
5. **Setup** — dealing, initial table state
6. **Gameplay** — turn sequence, core mechanics, sub-sections for each phase
7. **Scoring** — detailed point calculation with worked examples
8. **Winning** — game-level win condition (distinct from hand-level)
9. **Strategy Tips** — numbered list of practical advice
10. **Common Variations** — named variants with brief descriptions (if applicable)
11. **Terminology** — glossary of game-specific terms (if applicable)
12. **Example Hand Walkthrough** — concrete play-by-play (if applicable)

Not every game needs every section — use judgment, but the first 8 are expected.

### Style

- Use `**bold**` for key terms on first introduction.
- Use numbered lists for ordered sequences (turn steps, rankings) and bullet lists for unordered sets.
- Include concrete examples with suit symbols (♠ ♥ ♦ ♣) for clarity in gameplay sections.
- Card notation: spell out face cards in prose ("Jack of Hearts"), use shorthand in examples ("J♥", "10♠").
- Keep each file self-contained — don't reference other game files.

### Filename Convention

- Lowercase, no spaces or hyphens: `rummy500.md`, `euchre.md`.
- Use the most widely recognized short name for the game.
