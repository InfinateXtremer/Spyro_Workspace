# Spyro Model Workspace For SRT
A workspace with exported mesh, animations and Unreal Engine project

----

### Current Issues:
1. 2D eyes do not work, eyes are animated via bone instead of material curves.

----

## What is this project and what it is not:
* It's an entire recreation of skeleton and animations for Spyro.
* It is a framework for future Spyro animation mods and possibly models.
* It's not a playable character, this project only includes the model and animations.
* No animations.

----

Requirements:

**WWise 2018.1.11.6987** with Unreal Engine 4.19 integration or alternatively following modules:
* Apple > macOS
* Microsoft > Windows > Visual Studio 2015
* Microsoft > Windows > Visual Studio 2017

---

**Blender 2.8+** .BLEND files are provided to create your own custom animations. 

RumbleAnimations.blend > Crash Team Rumble Animations.
Spyro_3D_Eyes_Additives_Final.blend > Additive Animations and Poses.
Spyro_Animations_Finalizing.blend > Vanilla Animations.

---

## Other used tools:
io_scene_psk_psa 7.0.0
https://github.com/DarklightGames/io_scene_psk_psa/releases

## Custom Skeleton Requirements:
1. Bone names needs to match up with reignited one otherwise game will crash. TODO:Check and see which bone names crash the game.
2. Make sure sockets are created.
