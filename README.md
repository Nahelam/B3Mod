# B3Mod
A Burnout 3: Takedown mod powered by a hand-rewritten menu system reverse-engineered from a Burnout Dominator prototype debug menu.

<img width="2560" height="1396" alt="Burnout 3 - Takedown_SLES-52585_20260513214224" src="https://github.com/user-attachments/assets/7dc950d9-086c-4844-ab45-6a5659b786f2" />

## Still a WIP
The initial goal of this mod was to regroup all the various patches I made for Burnout 3.  
I'm working on it from time to time and there's still a lot to do.

## Requirements
**SLES-52585** or **SLUS-21050** version of the game.  
PCSX2 with the "Extended RAM" option enabled.  
Read [this](https://github.com/Nahelam/PS2-Game-Mods#pcsx2) if you don't know what to do with pnach files.

## Mod Menu
Press SELECT to open the mod menu.

## Replays
Recently I've been focusing on making the replay system work in all offline game modes and it went kinda well.  
- While on the replay screen you can toggle between different camera modes using Up and Down (D-Pad).  
- You can toggle between 5 camera modes for the player and 3 camera modes for AI.  
- You can also switch to other cars using Left And Right (D-Pad) and activate the free camera with START.  
- If you use the Takedown camera or aftertouch, the slow motion will still happen during replay.  
- The same goes for signature Takedowns, the game will still pause during replay.  
- If you don't want the camera to move during a Takedown or a crash check the replay menu.
- The replay input buffer capacity is currently set to 200KB, you can track its usage through the debug log.
 
You can now unleash the cinematic potential of the game.

[![Burnout 3: Takedown - Retail Replay Mod Showcase](https://github.com/user-attachments/assets/581b998d-54eb-4a32-b8d2-cf1422633007)](https://youtu.be/Aw3aIkPtp88 "Burnout 3: Takedown - Retail Replay Mod Showcase")
