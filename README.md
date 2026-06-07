# Zombie Shooter 3D

A browser-based 3D FPS zombie survival game built with Three.js.

## Play

Open `index.html` in a desktop browser, or `mobile.html` on a phone.
Play on [GitHub Pages](https://khannudomvirak.github.io/Zombie-Shooter/).

## Controls

### Desktop (`index.html`)

| Key | Action |
|-----|--------|
| WASD | Move |
| Mouse | Look |
| Left Click | Shoot |
| Shift | Sprint |
| 1-4 / Scroll | Switch weapon |
| R | Reload |
| Escape | Pause |

### Mobile (`mobile.html`)

| Control | Action |
|---------|--------|
| Left stick (drag) | Move |
| Right side (drag) | Look around |
| FIRE button | Shoot |
| 1-4 buttons | Switch weapon |
| RELOAD button | Reload |
| SPRINT button | Toggle sprint |

## Weapons

| Weapon | Damage | Fire Rate | Magazine | Reserve |
|--------|--------|-----------|----------|---------|
| Pistol | 1 | Semi | 12 | 36 |
| SMG | 0.6 | Auto | 25 | 100 |
| Shotgun | 2×3 pellets | Semi | 4 | 16 |
| Sniper | 5 | Semi | 3 | 12 |

## Zombies

Five visual types with varied stats — normal, fat (high HP), tall (ranged), runner (fast), tank (very high HP, slow). Zombies chase the player, deal contact damage, and scale in number each wave.

## Supply Drops

Each zombie drops one supply on death:

| Drop | Chance | Amount | Visual |
|------|--------|--------|--------|
| Pistol Ammo | 20-40% | +12 | Silver box |
| SMG Ammo | 20-40% | +25 | Green box |
| Shotgun Ammo | 10-15% | +6 | Orange box |
| Sniper Ammo | 10-15% | +3 | Purple box |
| Health | 20% fixed | +4 HP | Green cross |

Ammo pickups fill the magazine first, then overflow to reserve.

## Difficulty

| Setting | Easy | Normal | Hard |
|---------|------|--------|------|
| Zombie Damage | 4 | 8 | 12 |
| Wave Base Zombies | 2 | 3 | 5 |
| Wave Growth Multiplier | 1.5× | 2× | 3× |
| Spawn Interval | 800ms | 600ms | 400ms |
| Max Zombies Per Wave | 20 | 30 | 45 |
