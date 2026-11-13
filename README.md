# VR Physics Sandbox - builds

Download page for test builds of a standalone Meta Quest VR physics sandbox.

## Download

**[Download SandboxVR.apk](https://github.com/veilbrowser-git/vr-physics-sandbox/releases/download/v0.5.0/SandboxVR.apk)** (285 MB)

Current build: version 0.5.0. Development build, not yet confirmed on a headset.
All builds are listed under [Releases](https://github.com/veilbrowser-git/vr-physics-sandbox/releases).

## What is in 0.5.0

- Two real maps to choose from in Menu > Sim: an industrial **Workshop** (the new start) and an outdoor **Quarry** in daylight, with baked lighting, physical props and their own ambience. A third (concrete training facility) is coming.
- Real recorded gunshots, slide / magazine / pump sounds, brass cases landing, footsteps that change with the ground, recorded NPC pain voices, 3D sound with direction cues and room echo.
- A detailed new pistol with a moving slide, magazine and trigger; better muzzle flash, smoke and bullet impacts. Detailed rifle and shotgun next.
- NPCs breathe, shift their weight and look at you.
- Menu > Sim shows the frame rate and CPU / GPU times: please send me those numbers from the headset.

## What is in 0.4.2

- Your hands are attached to your arms: the arm ends exactly at the wrist in every pose, and the hand carries its own piece of forearm, so bending the wrist no longer opens a gap at the sleeve.
- The body leans and turns with you, and the shoulders reach forward on long reaches.
- NPC finger grabbing is reliable; several finger, fracture and grip bugs fixed (see the release notes).

## What is in 0.4.0

- NPC fingers are physical: every finger bone has its own joint, bends within limits, collides with objects and wraps around a handle.
- Reach for an NPC's finger and the segment you would grab is highlighted; hold grip to take it. Your pull is limited in strength.
- Each finger bone can fracture and each finger joint can be injured, separately. Injured fingers go weak, and a hand with injured fingers drops what it holds.
- Menu > NPC hand: choose left or right, set a pose (Open, Relaxed, Grip, Point), and read each finger's bone and joint condition.
- Menu > Sim: Save sandbox / Load sandbox, and "Go to the finger lab" (an NPC beside a table of handles and small objects).

## What is in 0.3.0

- You now have a body: look down to see a torso, arms that reach your hands, and legs that step and crouch with you.
- Eight modelled weapons: pistol, rifle, shotgun, baton, bat, hammer, machete, knife. Guns are on the table to your left at the start, melee weapons on the far table.
- Sound: gunshots, reloads, hits, cuts, falls, knocks and footsteps. NPCs grunt, cry out and groan when hurt.
- Bullet holes and cuts on NPCs, pock marks on walls, swelling and impact deformation, and glossier blood that sprays, pools and dries.
- From 0.2.0: physical NPCs that stand, stagger and fall, with bruises, wounds, bleeding and fractures per body part. Menu > Inspect shows injuries and lets you heal or reset.
- From 0.1.1: walking, teleport and grabbing work, and the controllers are realistic hands.

All sounds are synthesised and the weapon models use flat colours, so neither is photoreal yet.

## Install on a Quest

1. Open this page in the headset browser and tap the download link above.
2. Open a file manager (for example CX File Explorer), go to Downloads and tap `SandboxVR.apk`.
3. If asked, allow that app to install unknown apps, then tap Install. It installs over an older version.
4. Launch **VR Physics Sandbox** from App Library > Unknown Sources.

## Controls

| Action | Control |
| --- | --- |
| Walk | Left thumbstick |
| Teleport | Right thumbstick forward, aim the arc, release |
| Snap turn | Right thumbstick left / right |
| Grab / release | Grip button, with your hand touching the object or an NPC |
| Fire a gun | Trigger of the hand holding the grip (guns reload by themselves when empty) |
| Steady the rifle or shotgun | Grip the fore-end with your other hand |
| Open / close menu | Left Menu button or Y |
| Press menu buttons, place items, select an NPC | Point the other hand, pull the trigger |
| Heal / reset an NPC | Select it, then Menu > Inspect |
| Grab an NPC's finger | Reach for it until one segment is highlighted, then hold grip |
| Pose an NPC's hand, see finger injuries | Select the NPC, then Menu > NPC hand |
| Save / load, finger lab | Menu > Sim |
| Hand skin tone and alignment | Menu > Hands |

The NPC stands in the middle of the room.
