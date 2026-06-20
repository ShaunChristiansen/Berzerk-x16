# Berzerk-x16
Berzerk arcade port for the Commander X16
# Berzerk for the Commander X16

A faithful, hand-written **65C02 assembly** port of the 1980 Stern Electronics
arcade classic **Berzerk**, built for the [Commander X16](https://www.commanderx16.com/).

Shoot the robots, clear the rooms, and watch out for the electrified maze walls
and the unkillable Evil Otto.

## Download & play

Grab the latest **BERZERK-X16.zip** from the
[**Releases**](../../releases/latest) page.

The zip contains:

| File | Notes |
|------|-------|
| `BERZERK.PRG` | the game |
| `SPEECH.BIN`  | speech + sound-effect data **(required)** |
| `TITLE.BIN`   | title splash screen **(required)** |
| `README.txt`  | quick reference |

Put all of them in the **same folder** (or SD-card directory).

**Real hardware:** `LOAD"BERZERK.PRG"` then `RUN`
**Emulator:** `x16emu -prg BERZERK.PRG -run` (with all files in the same folder)

## Controls

- **SNES controller** — D-pad to move, any face button fires (all 8 directions)
- **Keyboard** — cursor/arrow keys to move, **X** to fire
- **F1** captions · **F2** god mode (can't die; score not saved)

## How to play

Shoot robots (50 pts each) and clear a room for a bonus. The maze walls —
**including the outer border** — are electrified and kill on contact; only the
door openings are safe. Avoid robot lasers and Evil Otto, who can't be killed
and speeds up once a room is cleared. High scores are saved to `BERZERK.HSC`.

## Credits

Created by **Shaun Christiansen** ("schristis") for the Commander X16 community.
Developed with assistance from **Claude AI**.

## A note on copyright

This is a **non-commercial fan tribute** made for preservation and hobby use on
the Commander X16. *Berzerk*, *Evil Otto*, and related names are trademarks of
their respective rights holders. This project is **not affiliated with, sponsored
by, or endorsed by** them. No original ROM code or assets are included — the game
was rewritten from scratch for the X16. If you are a rights holder and have any
concern, please get in touch and I'll act promptly.
