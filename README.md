# Dimm City solo games

Solo journaling games for [DC Solo RPG](https://github.com/dimm-city/dc-solo-rpg), set in Dimm City. Each game is one `.game.md` file at the root of this repository, with its card art in a folder of the same name beside it.

| Game | Where | Who you are |
| --- | --- | --- |
| `future-lost.game.md` | A ruined future | A time traveler stranded after the collapse, repairing the machine that can take them home |
| `last-light-in-the-burrows.game.md` | The Burrows, Deepwarren | A rat-folk patchhead keeping a drowning warren's pump-heart alive through the Black Rains |
| `drift-gate-seven.game.md` | Tech District, Etherwave Transit Hub | A cat-folk wirephreak carrying stolen evidence through a lockdown toward the one gate still cycling |

## Playing them

In the DC Solo RPG app, open **Settings → Game sources** and add `dimm-city/solo-rpg-games`. The games appear on the home screen beside the built-in ones. The app checks this repository for changes about once an hour.

## Adding a game

1. Write `your-game.game.md` following the [format guide](https://github.com/dimm-city/dc-solo-rpg/blob/main/docs/game-config.md): 1 Primary Success, 4 Failure Counters, 3 Narrative, 16 Challenge and 28 Event cards.
2. Put any card art in `your-game/` and reference it from a card with a markdown image on its own line, by a relative path: `![alt text](your-game/picture.svg)`.
3. Commit to `main`. Nothing else to update.

The art here is vector (SVG) scenes in the app's palette, so the files stay small; PNG or JPG work too.
