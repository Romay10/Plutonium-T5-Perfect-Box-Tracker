# Plutonium T5 Perfect Box Tracker

Custom patch for **Call of Duty: Black Ops 1 Zombies / Plutonium T5**.

This project adds a **Perfect Box setup** and an integrated **Box Hits Tracker HUD** for practice, high round routing, reset-heavy attempts and checking box luck during a game.

The tracker is built directly into the patch, so no external `.exe` is required.

## Features

- Perfect Box / First Box logic for BO1 Zombies
- Custom weapon order for every Zombies map
- Integrated in-game Box Hits Tracker HUD
- Tracks total box hits
- Tracks good weapon hits
- Tracks good hit percentage
- Tracks individual good weapon percentages
- Teddy/joker counts as a box hit but not as a good weapon
- No external `.exe` required
- Twitch/spam messages removed
- Designed for Plutonium T5 Zombies

## Download

Download the latest release from the **Releases** section of this repository.

The file you need is:

```txt
common_zombie_patch.ff
```

Do **not** download the source code `.zip` if you only want to install the patch.

## Installation

Place the file in:

```txt
%localappdata%\Plutonium\storage\t5\zone
```

Make sure the file is named exactly:

```txt
common_zombie_patch.ff
```

Back up your original `common_zombie_patch.ff` before replacing it.

## Known Issues

Animated camo packs, custom weapon skins or other weapon-related mods may conflict with the Mystery Box logic.

If the HUD appears but the box weapon is invisible or the player does not receive the weapon, try testing the patch with no other BO1 Zombies mods installed.


## Usage

1. Download `common_zombie_patch.ff` from the Releases section.
2. Place it in `%localappdata%\Plutonium\storage\t5\zone`.
3. Launch Plutonium T5.
4. Load a Zombies map.
5. Use the Mystery Box normally.
6. The Box Hits Tracker HUD should update automatically in-game.

## Important Notes

This patch is intended for:

- Practice
- Custom games
- Route testing
- High round preparation
- Reset-heavy attempts
- Box luck tracking

Do not use this for official leaderboard submissions unless the category rules explicitly allow patched gameplay.

## Disclaimer

This project is not affiliated with Activision, Treyarch or Plutonium.

## Credits

Based on existing BO1/T5 Zombies first box patch work, with custom weapon order changes, spam removal and an integrated Box Hits Tracker HUD added for practice and routing.

Special thanks to the BO1 Zombies and Plutonium communities.
