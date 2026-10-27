# Tekken5-DR-Online-Framedata-Overlay-for-RPCS3
Tekken 5 DR Online Framedata Overlay for RPCS3

Real-time frame data overlay and user experience patches for **Tekken 5: Dark Resurrection Online** running in **RPCS3** (PS3 emulator).

> **EDUCATIONAL / RESEARCH USE ONLY**
> This project is free and provided strictly for educational and research purposes.
> This project does not contain the game itself, its game image, or anything similar. To use this tool, you must own a legitimate, licensed copy of the game.
> Provided **AS-IS**, without warranty of any kind. Use at your own risk.
> Read LICENSE file for information about license.

---

## Supported versions:

| Game                        | Title ID    | Reg |
|-----------------------------|-------------|-----|
| Tekken 5: Dark Resurrection | `NPEA00019` | EU  |
| Tekken 5: Dark Resurrection | `NPUB30009` | US  |

The game version is **detected automatically** no manual selection needed.
NOTE: Some minor extra effects do not work in the US version.
---

## Features:

### User experience patches:
- **Position reset** (`Select + Cross`) for practice mode - reset characters positions to their start positions. Also preserves all training settings across the reset.

### Framedata:
- Real-time display for **both P1 and P2**:
  - `STARTUP` - first and last hitbox-active frames
  - `ACTUAL` - frame the hit actually connected
  - `HITDIST` - hit distance
  - `ADV` - frame advantage on block
  - `RANK` - attack level (`HIGH`, `MID`, `SMID`, `LOW`, `UNBLK`, `THROW`)
- `DISTANCE` - current separation between fighters
- KNOWN ISSUES: moves of the "uf+3" type (such as those used by Heihachi or Hwoarang) are calculated incorrectly.
              Also several other complicated moves need to be resolved in future updates.

### Character & stage control:
- **Character swap** for P1 and P2 (any playable ID, including bosses and unplayables)
- **To play Jinpachi on P1 side online** - both players need to enable character swap P1 (Jinpachi) (same if for P2)
- **Stage swap** (any stage ID)
- **Stage type** - you can change wall types: Walls / Noclip / Infinite
- **Attack-type override** - force the current attack to be treated as `HIGH`, `MID`, `SMID`, `LOW`, `UNBLK` or `THROW`
- **Demo-location** - swap the training dummy background / demo stage (only in EU version)

### Player control:
- **Speed override** per player
- **Hide P1** / **Hide P2**
- **Invisibility**, **Show HP percent**, **Show/Hide UI**
- **Manual Counter Hit**, **Sparks** and **hitstop** toggles

### Camera:
- **Camera distance** - real-time control (no photo mode required)
- **Free-fly camera** (only in EU version)
- **Cinema camera** mode
- **Photo mode** toggle

---

## Hotkeys:

| Key | Action |
|-----|--------|
| `Shift + G` | Reset overlay window to default position |
| `Drag top bar` | Move overlay window |
| `L3` (click L-stick) | Toggle photo mode (enable Free Fly mode and use D-pad for camera move, R1 speed modifier, right buttons for directions modifiers) |
| `Select + Cross` | Reset positions in training |
| `Right-click on move name` | Copy the move's internal name |

---

## Buttons:

| Button | Action |
|--------|--------|
| `INFO` | About window |
| `EXTRAS` | Extra effects, camera, invisible / cinema / freefly / slowmo etc. |
| `X` | Close overlay |

---

## Requirements

- Windows 10/11 x64
- .NET Framework 4.5+
- RPCS3 with **Tekken 5: Dark Resurrection** (`NPEA00019` or `NPUB30009`)
---

## License

MIT License (read LICENSE file)

---

## Credits

- Dmitry Raskalof aka **TEKKEN ОНЛИФАНС** — original development
- DONATE: https://boosty.to/tekken_onlyfans
