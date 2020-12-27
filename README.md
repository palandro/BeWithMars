# Marsland
Technical development repository for the VR application "Marsland" - a VR application where you can explore and learn about the Mars InSight Lander from NASA.

<i>Disclaimer</i>
This project is not created or managed by NASA. This is a private project made by an indie developer.

Here you can find some info about the project and download some test apk's for the Oculus Quest.

Please note that the application is under development and even basic functionality is lacking at the moment. 

If you want to know more about the Mars InSight Mission please visit:
https://mars.nasa.gov/insight/

You can follow the development log and comment on the progress on itch.io:
https://vicator.itch.io/marsland

You will soon be able to install the application via SideQuest.


### Usage (v0.0.4)
Locomotion schemes:
 - Walk freely, Teleporation, Smooth Locomotion (also called Continous Locomotion)
 
Buttons:
 - A: Unfold/fold solar array
 - B: Open Instrument Deployment Arm, pickup the Seismometer and place it on the Mars ground (autoplay)
 - Start: Open Options menu on left hand
 - Left Thumbstick: Smooth locomotion
 - Right Thumbstick: Snap turn


# Release notes

## v0.0.4 - Oculus Quest Build
https://github.com/palandro/Marsland/releases/tag/v0.0.4
### Features:
(Added) Teleportation locomotion (default locomotion mode)

(Added) Options menu. With sections for Locomotion, Credits and About. The menu attaches to the left hand.

(Added) Option to switch between Teleportation and Smooth Locomotion.

(Added) Laser aim pointer on right hand.

(Added) Field-of-view limiter when Smooth Locomotion is active. Dynamic, based on locomotion speed.

(Added) Grid to hinder user from locomoting too far away into the landscape.

(Changed) Upgraded to use Unity 2019.4.16f1.

(Changed) Upgraded to use Oculus Integration for Unity v23.0. The Oculus Quest 2 will now run the app at 90 Hz.

(Changed) Removed remaining objects in scene that were wrongly using the Lit shader.

(Changed) Replaced Quad mesh with Box mesh to instead use primitive box colliders for the surrounding landscape barrier.

(Removed) Removed unused Oculus resources (Avatar, Lipsync). Saving approx 6 MB on textures and 3.5MB on shaders.


## v0.0.3 - Oculus Quest Build
https://github.com/palandro/Marsland/releases/tag/v0.0.3
### Features:
(Added) Simple flashlight on the wrist of the right hand. Non-volumetric. For investigating hull and parts below the science deck.

(Added) Auto-play animation (on the press of a button) where the Instrument Deployment Arm opens up, lifts up the seismometer and puts it on the Mars ground.

(Added) Simple signs with questionmarks. At the moment they act as placeholders for future interesting components on the lander which the user will be able to investigate and learn more about.

(Changed) Surrounding landscape to use separate material to omit it from shadow map generation pass.

(Fixed) Changed multiple objects to use the URP Simple Lit shader. Some were using the Lit shader as well as the Standard shader.

(Fixed) Changed hands to use the URP Simple Lit shader.


## v0.0.2 - Oculus Quest Build
https://github.com/palandro/Marsland/releases/tag/v0.0.2
### Features:
(Changed) Unfold the solar array using the A-button on the right hand controller. The two arms and their respective solar arrays unfold completely using the same button.

(Added) After being unfolded, the solar array can be folded back in again using the A-button.

(Added) Surrounding landscape.

(Added) Collider hindering the user from being able to transition inside the lander using smooth locomotion. The user can however freely walk inside the lander manually.


## v0.0.1 - Oculus Quest Build
https://github.com/palandro/Marsland/releases/tag/v0.0.1
### Features:
(Added) Walk around the lander

(Added) Extend the two arms that carry the solar arrays: X-Button (right hand controller)

(Added) Open the solar arrays themselves: Y-Button (right hand controller)


