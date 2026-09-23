# Blood&Serum

A 3D first-person horror survival game built in Unity.

## About

An abandoned village overrun by zombies. The player must scavenge weapons, survive waves of undead, and retrieve the vaccine that could save humanity. Progress through the level to find better weapons and face increasingly dangerous encounters.

## Features

- **First-Person Combat** — Knife, pistol, shotgun, molotovs, etc
- **Custom Zombie AI** — 4-state FSM: Idle, Patrol, Eating, Attacking
- **AI Behaviors:**
  - Patrol using set points around the map
  - React to player proximity — chase and attack
  - React to sound — investigate bottle throws
  - Stunlock on melee hits
  - Lose track of player hiding behind furniture
  - Humanized variation between zombies
- **Wave Spawning** — Trigger-based enemy waves as player progresses
- **Visual Effects** — Lighting, LOD optimization, flashlight, night vision

## Controls

| Key | Action |
|-----|--------|
| WASD | Move |
| Mouse | Look |
| LMB | Attack |
| RMB | Hold to Aim |
| F | Flashlight |
| N | Night Vision |
| V/B | Toggle FPS display |
| I | Open/Close Inventory |

## Tech Stack

- **Engine:** Unity 3D
- **Language:** C#

## Known Limitations

- Vertical slice — mechanics complete but level design unfinished
- Wave trigger areas and weapon placements need some polish

## License

This project was developed for academic purposes.
