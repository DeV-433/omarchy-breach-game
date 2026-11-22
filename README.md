# Breach

A neon arena first-person shooter for [Omarchy](https://omarchy.org)'s Game Vibes. Fight sector after sector of a hostile grid, pick an upgrade after each one, and topple a boss every fifth sector: a Warden and the Thumper by turns. It runs endlessly: your score and the furthest sector you reach are saved, along with your best runs.

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

- **Sectors and bosses.** Waves of enemies teleport in, with a warning before each one arrives. Clear a sector to pick one of three upgrades. Every fifth sector holds a boss: a Warden at sectors 5, 15, 25…, the Thumper at 10, 20, 30….
- **Enemies.** Drones, gunners, chargers, brutes that split when killed, crawlers that slither along the ground and rear up to bite, lancers that aim a laser before firing, bulwarks that hide behind shields, and, once the first Warden falls, mini-thumpers that rush to your side and blast a short-range shockwave along the floor.
- **Wardens.** Bosses that fire fans and spirals of shots, summon minions, sweep a towering laser wall across the arena (too tall to jump: run for its gap or dash through it), and drop turrets that sweep beams along the floor.
- **The Thumper.** A boss that rushes to your side in an instant, charges, and blasts a shockwave across the whole arena, then stands spent for two seconds, taking double damage, before it comes again, leaving lesser enemies behind wherever it set off from.
- **Jumping.** Rings and beams that travel along the floor can only be jumped, or dashed through. A JUMP warning closes in under the crosshair as one approaches, and turns red at the moment to jump.
- **Weapon mods.** Enemies sometimes drop Scatter (a shotgun that loads shell by shell), a Railgun, or Storm (a rapid-fire minigun). A mod lasts until the sector ends, and each has its own crosshair and recoil.
- **Ammo.** Ammo is limited, and enemies drop more when you run low. When you're completely out, a last-chance reload appears. Miss it, and you have to reach an ammo cache somewhere in the arena while enemies hunt you.
- **Settings.** Mouse sensitivity, invert Y, field of view, volume, music, screen shake, difficulty, auto reload, bloom and an FPS counter.
- **Difficulty.** Easy, Normal or Hard, set in the settings and locked in when a run starts. Each step changes how hard enemies hit, how tough, fast, numerous and trigger-happy they are, how often repairs and ammo drop, how many spare magazines you start with, how wide the reload windows are, and how much every point is worth: Easy scores ×0.6, Hard ×1.6. Past runs show which mode they were played on.
