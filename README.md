# Spyro Model Workspace For SRT
A workspace with exported mesh, animations and Unreal Engine project

#### We ask you to not use this project in paid projects/commissions as these assets are recreations but if you will please include a link to this project.


----

## What is this project and what it is not:
* It's an entire recreation of skeleton and animations for Spyro.
* It is a framework for future Spyro animation mods and possibly models.
* It doesn't recreates main character material (yet)
* It's not a playable character, this project only includes the model and animations.


----

Requirements:

**WWise 2018.1.11.6987** with Unreal Engine 4.19 integration or alternatively following modules:
* Apple > macOS
* Microsoft > Windows > Visual Studio 2015
* Microsoft > Windows > Visual Studio 2017

TODO:

* Animate all the additive animations.
* Add all the missing animation notifiers.
* Create a blend file with Spyro's mesh.
* Create 3D eyes or animate 2D eye curves.

Anim Notify Information:

* AkEvent, plays the provided sound
* FootStepEvent, self-explanatory has two variables that defines which foot is used for the event and if it is a right foot.
* PS_, particle system events.

---

## How to migrate your old models - (Untested) (TODO: Explain more detail)

1. Open your model in umodel
2. Export it with default settings
3. Using Blender 2.79b with PSK importer script
4. Import your model to blender make sure Reorient bones and Reorient directly options are check
5. **Change your root bone's rotation to 0 (Head X,Y,Z = 0 - Tail X,Z = 0 Y = 1)**
6. Export your model as fbx with scale set to 0.01 and Add Leaf Bones option unchecked
7. Import it to this project.
8. While in import settings select SKEL_CPS1999_Spyro from the skeleton selection.
9. Cook and pak only your model.
