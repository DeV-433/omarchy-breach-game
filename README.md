# Breach

A neon arena first-person shooter for [Omarchy](https://omarchy.org)'s Game Vibes. Fight sector after sector of a hostile grid, pick an upgrade after each one, and topple a Warden every fifth sector. It runs endlessly: your score and the furthest sector you reach are saved, along with your best runs.

It's one HTML file built on three.js. It takes on your desktop's Omarchy theme, with glowing bloom in dark themes.

## Install

On Omarchy, open the menu and go to **Install > Gaming > Game Vibes**, then paste this repository's URL. Or run:

```bash
omarchy games vibes install https://github.com/DeV-433/omarchy-breach-game
```

Breach then appears in Game Vibes in the app launcher (Super + Space).

## Controls

| Key | Action |
|---|---|
| W A S D | Move and strafe |
| Mouse | Aim (click the game to capture the mouse) |
| ← → / ↑ ↓ | Turn / move, for keyboard-only play |
| Left click / F | Fire (hold) |
| Right click | Aim down sights (hold): zoom in, steadier aim |
| Space | Jump: onto low cover, over rings and crawlers; land on enemies to stomp them |
| R | Reload; press R again while the cursor is in the bright zone for a perfect, overcharged reload |
| Shift | Dash, untouchable while dashing |
| E | Nova blast, charged by kills |
| 1 2 3 | Pick an upgrade after a sector (or ← → and Space, or click) |
| [ ] | Mouse sensitivity |
| ? | Settings and controls |
| Esc / P | Pause and resume |
| Q (while paused) | Back to Game Vibes |
| M | Sound on or off |

## What's in it

- **Sectors and Wardens.** Waves of enemies teleport in, with a warning before each one arrives. Clear a sector to pick one of three upgrades. Every fifth sector holds a Warden boss.
- **Enemies.** Drones, gunners, chargers, brutes that split when killed, crawlers that slither along the ground, thumpers that leap and slam shockwaves across the floor, lancers that aim a laser before firing, and bulwarks that hide behind shields.
- **Wardens.** Bosses that fire fans and spirals of shots, summon minions, slam down to send shockwave rings across the arena, and drop turrets that sweep beams along the floor.
- **Jumping.** Rings and beams that travel along the floor can only be jumped. A JUMP warning closes in under the crosshair as one approaches, and turns red at the moment to jump.
- **Weapon mods.** Enemies sometimes drop Scatter (a shotgun that loads shell by shell), a Railgun, or Storm (a rapid-fire minigun). A mod lasts until the sector ends, and each has its own crosshair and recoil.
- **Ammo.** Ammo is limited, and enemies drop more when you run low. When you're completely out, a last-chance reload appears. Miss it, and you have to reach an ammo cache somewhere in the arena while enemies hunt you.
- **Settings.** Mouse sensitivity, invert Y, field of view, volume, music, screen shake, difficulty, auto reload, bloom and an FPS counter.
