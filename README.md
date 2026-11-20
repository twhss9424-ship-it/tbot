# Triggerbot (Fabric)

Auto-attacks the entity you are aiming at, with cooldown and interval controls.

This mod is intended for singleplayer or private servers with explicit consent. It is **not** for cheating in public servers. If you use it in multiplayer, **other players must be aware**, and the server host/admin **must approve** it.

## Features
- Toggleable triggerbot.
- Optional attack targets: players and/or mobs.
- Attack interval and cooldown checks.
- Simple in-game config screen.

## Requirements
- Minecraft 1.21.11
- Fabric Loader 0.18.3
- Fabric API (matching 1.21.11)

## Install
1. Build or download `triggerbot-1.0.0.jar`.
2. Place it in your `.minecraft/mods` folder.
3. Launch with Fabric.

## Usage
- Toggle triggerbot: `G`
- Open settings: `H`

When enabled, it attacks the entity you are aiming at (within normal reach) on your configured interval.

## Config
You can edit the file directly or use the in-game screen.

File: `config/triggerbot.json`

Example:
```json
{
  "enabled": true,
  "attack_players": true,
  "attack_mobs": true,
  "attack_interval_ticks": 4,
  "require_cooldown_ready": true
}
```

## Ethical Use
This mod is **NOT** for cheating on public servers. Use it only in:
- Singleplayer
- Private servers where **all players know** you are using it
- Servers where the **host/admin explicitly approves** its use

If the server host or other players do not consent, **DO NOT** use this mod. 

## Disclaimer
Any damage, loss, or consequences caused by improper or unauthorized use of this mod are the sole responsibility of the user.