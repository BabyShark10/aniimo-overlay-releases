# Translations

AniimoOverlay's English text comes from two files. Corrections and additions are welcome — open an issue with the changed lines, or attach an edited file.

| File | What it holds | How to edit |
|---|---|---|
| `en.json` | Interface text. Key = Korean original, value = English. | Fix the English value. Keep `%1`, `%2` … placeholders and line breaks (`\n`) exactly as in the Korean key — they are filled in by the app. |
| `en_data.json` | Game-data sentences that are **still shown in Korean** in English mode (hand-written quest steps, "how it spawns" notes, a few tooltips). Value `""` = not translated yet. | Put the English sentence in the value. `**bold**` markers in the Korean key mark names/requirements the app highlights — keep them around the same words. |

Names of Aniimo, items, facilities, areas, skills and traits are taken from the game's own English localization and are not in these files. If one of them looks wrong, please mention it in an issue instead.

Both files are regenerated from the source repository on every release, so edits sent here are merged by the maintainer rather than committed directly.
