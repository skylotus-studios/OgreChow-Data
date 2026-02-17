# Ogre Chow Balance Sheet

>  Master the onion. Perfect the chow. Raise the heat. How far can your hands take you?🧅🔥

**Ogre Chow** is a silly, skill-forward incremental cooking game about mastering a single ingredient: **onion**.  
This repository is the **public, read-only distribution mirror** for live-tunable game data (balance, drop rates, upgrades, patch notes, etc.).

---

## Description

This repo contains **data only**:
- Economy parameters
- Drop rates & scaling
- Upgrade definitions (costs, multipliers, floors/ceilings)
- Tool grades & weights
- Difficulty curve knobs per minigame
- Patch notes

This repo is intended to be:
- **Publicly viewable** (players can see how balance works)
- **Readable** (configs + patch notes are human-friendly)

This repo also aims for the following:

✅ The source of truth for the game remains **secure**.  
✅ This repo is the **published output** players download.

---

<!-- PATCH_NOTES_START -->
## Patch Notes

### v0.0.1 — Initial Balance Publish

```text
Initial balance publish.

Gold:
  Base Multiplier: 2
  Bonus Multiplier Boil: 0.01
  Bonus Multiplier Chop: 0.01
  Bonus Multiplier Mash: 0.01
  Bonus Multiplier Stir: 0.01

Heat:
  Base Heat: 40
  Heat Multiplier Per Level: 0.002
  Heat Per Level Increment: 10

Inferno:
  Base Inferno Level1 Chance: 80%
  Base Inferno Level2 Chance: 120%
  Chance Growth Factor: 15%
  Epic Inferno Level: 1
  Highest Inferno Tier Cap: 25
  Legendary Inferno Level: 3
  Lowest Inferno Tier Cap: 15
  Mythic Inferno Level: 4
  Perfect Inferno Level: 5
  Roll Chance Increment Per Inferno Level: 50%
  Ultimate Inferno Level: 2

Tools:
  Boil Speed: 1/1.2/1.5/1.9/2.2/2.5/2.75
  Boil Window: 45/35/25/15/10/5/3
  Chop Precision: 30/26/22/18/14/12/14
  Chop Time: 2/1.9/1.8/1.7/1.6/1.55/1.5
  Grade Chance: 70/22/6/1.6/0.35/0.05/0.01
  Mash Time: 15/10/7/6/5.5/5/4
  Stir Sensitivity: 5/7/10/12/15/18/20
  Stir Window: 45/35/25/15/10/5/3

Upgrades:
Boil Automation:
  Value: 1
  Decay: 1
  Base Cost: 6000
  Cost Growth: 1.24
  Cap: 25

Boil Floor:
  Value: 1
  Decay: 1
  Base Cost: 1000
  Cost Growth: 1.4
  Cap: 20

Boil Gold Multiplier:
  Value: 0.005
  Decay: 0.9
  Base Cost: 5000
  Cost Growth: 1.35
  Cap: 25

Chop Automation:
  Value: 1
  Decay: 1
  Base Cost: 6000
  Cost Growth: 1.24
  Cap: 25

Chop Floor:
  Value: 1
  Decay: 1
  Base Cost: 1000
  Cost Growth: 1.4
  Cap: 20

Chop Gold Multiplier:
  Value: 0.005
  Decay: 0.9
  Base Cost: 5000
  Cost Growth: 1.35
  Cap: 25

Global Ceiling:
  Value: 1
  Decay: 1
  Base Cost: 50
  Cost Growth: 1.75
  Cap: 23

Global Ceiling Lvl1:
  Value: 1
  Decay: 1
  Base Cost: 6
  Cost Growth: 1
  Cap: 1

Global Ceiling Lvl2:
  Value: 1
  Decay: 1
  Base Cost: 15
  Cost Growth: 1
  Cap: 1

Global Gold Multiplier Rate:
  Value: 20%
  Decay: 1
  Base Cost: 50
  Cost Growth: 1.8
  Cap: 23

Global Gold Multiplier Rate Lvl1:
  Value: 20%
  Decay: 1
  Base Cost: 6
  Cost Growth: 1
  Cap: 1

Global Gold Multiplier Rate Lvl2:
  Value: 20%
  Decay: 1
  Base Cost: 15
  Cost Growth: 1
  Cap: 1

Mash Automation:
  Value: 1
  Decay: 1
  Base Cost: 6000
  Cost Growth: 1.24
  Cap: 25

Mash Floor:
  Value: 1
  Decay: 1
  Base Cost: 1000
  Cost Growth: 1.4
  Cap: 20

Mash Gold Multiplier:
  Value: 0.005
  Decay: 0.9
  Base Cost: 5000
  Cost Growth: 1.35
  Cap: 25

Onion To Nugget Ratio:
  Value: 0.02
  Decay: 1
  Base Cost: 3000
  Cost Growth: 1.2
  Cap: 25

Pull Automation Rate:
  Value: 10%
  Decay: 1
  Base Cost: 5000
  Cost Growth: 1.22
  Cap: 10

Seal Point:
  Value: 1
  Decay: 1
  Base Cost: 5000
  Cost Growth: 1.3
  Cap: 30

Stir Automation:
  Value: 1
  Decay: 1
  Base Cost: 6000
  Cost Growth: 1.24
  Cap: 25

Stir Floor:
  Value: 1
  Decay: 1
  Base Cost: 1000
  Cost Growth: 1.4
  Cap: 20

Stir Gold Multiplier:
  Value: 0.005
  Decay: 0.9
  Base Cost: 5000
  Cost Growth: 1.35
  Cap: 25
```

<!-- PATCH_NOTES_END -->

---

## Repo layout

```text
OgreChow-Data/
  config/
    version.json
    balance.json
    patch_notes.json
  README.md
  LICENSE.md
