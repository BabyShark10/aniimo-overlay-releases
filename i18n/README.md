# Translations

AniimoOverlay's English text comes from two files in this folder. Corrections are welcome — you don't need to know anything about the code.

| File | What it holds |
|---|---|
| `en.json` | Interface text (buttons, labels, tooltips). Key = Korean original, value = English. |
| `en_data.json` | Sentences written by the maintainer for game data: quest steps, "how it spawns" notes, personality (MBTI) tips, item sources. Key = Korean original, value = English. |

Names of Aniimo, items, facilities, areas, skills and traits come from the game's own English localization and are **not** in these files. If one of them looks wrong, mention it in an issue instead.

## How to help

1. Open `en.json` or `en_data.json` here on GitHub and use the browser's find (Ctrl+F) to locate the English text you saw in the overlay. Every line looks like this:

   ```
   "한국어 원문": "English text shown in the overlay",
   ```

2. Only the part **after the colon** (the English value) needs changing. Leave the Korean key exactly as it is — the app uses it to look the line up.
3. Send the fix in one of two ways:
   - **Comment on an issue** with the lines you changed, e.g.

     ```
     "다시 실행하면 적용돼요": "Takes effect after restarting the overlay"
     ```

     (old English → new English in plain words is fine too, as long as it's clear which line you mean), or
   - download the file, edit it in any text editor, and **attach the edited file** to an issue.
4. A screenshot of where the text appears helps a lot when the wording depends on context.

Rules that keep the app working:

- Keep `%1`, `%2` … placeholders exactly as in the Korean key — the app fills them in (numbers, names).
- Keep line breaks (`\n`) where the Korean key has them.
- Keep the `**bold**` markers in `en_data.json` around the same words (names, requirements) — the app highlights them in yellow.

Both files are regenerated from the source repository on every release, so fixes sent here are merged by the maintainer and appear in the next update.
