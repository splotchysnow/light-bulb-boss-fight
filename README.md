# Light Bulb Boss Fight

A single-level boss fight demo built in Unity, inspired by the fixed-camera perspective of classic Resident Evil games. All assets — including the 3D boss model, music, and sound design — were created from scratch.

## Gameplay

The player faces off against a light bulb boss in a third-person arena. The boss sits at one end and fires projectiles downward toward the player, who must dodge and shoot back.

```
[ BOSS ]

  * * *       ← projectiles in various wave patterns
   * * *
    * * *

[ PLAYER ]
```

**Camera System**
- Fixed camera angles in the style of classic survival horror
- Press a button to switch between multiple camera positions, each giving a different tactical view of the arena

**Boss Attack Patterns**
- Sine wave projectiles
- Cosine wave projectiles
- Straight-line shots
- Back-and-forth oscillating shots
- Various other motion patterns that escalate over the fight

**Player Actions**
- Shoot at the boss
- Dodge incoming projectiles

## What I Made

Everything in this project was built by hand:
- 3D boss model (original)
- Original music and sound effects composed for the game
- Projectile motion system using trigonometric functions
- Dynamic multi-angle camera switching system

## Status

Single-level playable demo. Built in Unity with C#.

## How to Run

Open the project in Unity (tested on Unity 2020+) and load the main scene from the `Assets` folder.
